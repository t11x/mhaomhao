<template>
  <div id="app">
    <div id="navi">
        <nav class="navbar" role="navigation" aria-label="main navigation">
          <div class="container">
          <div class="navbar-brand">
            <a class="navbar-item has-text-warning is-size-5">
            MhaoMhao
            </a>
          </div>

          <div id="navbarBasicExample" class="navbar-menu">
           <div class="navbar-end">
            <a class="navbar-item">
              รายการประมูล
            </a>
            <a class="navbar-item">
              การจ้างงาน
            </a>
            <a class="navbar-item">
              บัญชี
            </a>
            <a class="navbar-item">
              ขนส่งสินค้า
            </a>
            <a class="navbar-item">
              รายงาน
            </a>
            <div class="navbar-item">
              <font-awesome-icon icon="coffee" />
            </div>
           </div>
          </div>
          </div>
        </nav>
    
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#navbar {
  width: 100%;
}
</style>
