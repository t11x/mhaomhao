<template>
  <div class="ChooseFarm">
    <div class="container">
    <h1>เปิดประมูลสินค้า</h1>
    <div class="card-container">
    <FarmBox msg="Hi"/>
    </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import FarmBox from '@/components/FarmBox.vue'

export default {
  name: 'ChooseFarm',
  components: {
    FarmBox
  }
}
</script>

<style lang="scss" scoped>
  .card-container{
    display: flex;
    justify-content: space-between;
  }
</style>

