<template>
<!-- <h1>{{ msg }}</h1> -->
  <div class="card-container">
    <div class="farm-card">
      <div class="farm-pic">//pic</div>
      <div class="farm-desc">
        <div class="farm-name">Farm Name</div>

      </div>
    </div>
  </div>  
</template>

<script>
export default {
  name: 'FarmBox',
  props: {
     msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .card-container{
    display: flex;
    justify-content: space-between;
  }
  .farm-card{
    margin-top: 10px;
    width: 200px;
    height: 500px;
  }
  .farm-pic{
    position: relative;
    height: 100px;
    overflow: hidden;
  }
  .farm-desc{
    padding: 0;
    margin-top: 5px;
  }
  .farm-name{
    font-size: 50px;
    font-weight: bold;
  }
</style>
