<template>
  <div class="ChooseFarm">
    <div class="container">
    <h1>เปิดประมูลสินค้า</h1>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'ChooseFarm',
  components: {
    HelloWorld
    // ,Navbar
  }
}
</script>
