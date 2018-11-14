<template>
  <div id="app">
    <router-view/>
    <footer class="footerz">
  <div class="content has-text-centered">
    <p>
      <strong>X</strong> by <a href="https://jgthms.com">Jeremy Thomas</a>. The source code is licensed
      <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The website content
      is licensed <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY NC SA 4.0</a>.
    </p>
  </div>
</footer>
  </div>
</template>
<script>
</script>
<style lang="scss">
#app {
  font-family: "Prompt", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#navbar {
  width: 100%;
}
.logo {
  display: flex;
  font-size: 20px;
  text-align: center;
  align-items: center;
  font-weight: 600;
  color: #ffb302;
}
.footerz {
  margin-top: 50px;
  box-shadow: 3px 3px 3px 3px;
  height: 20px;
  padding: 1rem;
  padding-bottom: 2.5rem;
  background: white;
}
</style>
