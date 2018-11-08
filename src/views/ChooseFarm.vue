<template>
  <div class="ChooseFarm">
    <div class="container">
      <div class="auc-title">เปิดประมูลสินค้า</div>
    <div class="card-container">
    <FarmBox msg="Hi"/>
    <FarmBox msg="Hi"/>
    <FarmBox msg="Hi"/>
    <FarmBox msg="Hi"/>
    <FarmBox msg="Hi"/>
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
    // flex-wrap: wrap;
    flex-flow: row wrap;
    justify-content:space-around;
    align-items:flex-start;
    background-color: white;
    padding: 15px;
    height: 150%;
  }
  .auc-title{
    display: flex;
    font-size: 27px;
    font-weight: 500;
    justify-content: flex-start;
    margin-left: 5%;
    margin-top: 1.2%;
    margin-bottom: 1.2%;

  }
</style>

