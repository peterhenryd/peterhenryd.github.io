<template>
  <div>
    <!-- main nav -->
    <div class="nav">
      <h2>peterhenryd</h2>
    </div>

    <a href="https://github.com/peterhenryd">github</a>
    <a href="mailto:peter@peterhenryd.me">email me</a>

    <br />
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200&family=Roboto+Mono:wght@300&display=swap');

body {
  margin: 75px 30%;
  font-family: 'Roboto', monospace;
}

.nav {
  background-color: #70b2c2;
  padding-top: 15px;
  padding-bottom: 15px;
  margin-bottom: 50px;
  font-weight: bold;
}

.nav h2 {
  margin: 20px;
  display: inline;
  color: white;
}

a {
  display: block;
  color: black;
  margin-bottom: 5px;
}
</style>