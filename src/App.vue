<template>
  <div id="app">
    <div id="navi">
        <nav class="navbar" role="navigation" aria-label="main navigation">
          <div class="container">
          <div class="navbar-brand">
            <a class="logo">
            MhaoMhao
            </a>
          </div>

          <div id="navbarBasicExample" class="navbar-menu">
           <div class="navbar-end">
            <a class="navbar-item">รายการประมูล</a>
            <a class="navbar-item">การจ้างงาน</a>
            <a class="navbar-item">บัญชี</a>
            <a class="navbar-item">ขนส่งสินค้า</a>
            <a class="navbar-item">รายงาน</a>
            <div class="navbar-item">
            <user-icon width="20px" height="20px" />
            </div>
           </div>
          </div>
          </div>
        </nav>
    
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
    </div>
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
import UserIcon from '@/assets/icons/user-solid.vue'
export default {
  components:{
    UserIcon
  }
}
</script>


<style lang="scss">
#app {
  font-family: 'Prompt', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#navbar {
  width: 100%;
}
.logo{
  display: flex;
  font-size: 20px;
  text-align: center;
  align-items: center;
  font-weight: 600;
  color: #FFB302;
}
.footerz{
  margin-top: 50px;
  box-shadow: 3px 3px 3px 3px;
  height: 20px;
  padding: 1rem;
  padding-bottom: 2.5rem;
  background: white;
}
</style>
