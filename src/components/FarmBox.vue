<template>
<!-- <h1>{{ msg }}</h1> -->
    <div class="farm-card">
      <div class="farm-pic">//pic</div>
      <div class="farm-desc">
        <div class="farm-name">Farm Name</div>

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

  .farm-card{
    width: 150px;
    background-color: white;
    flex-basis: 30%;
    padding: 20px;
    margin-bottom: 20px;
  }
  .farm-card:hover{
    box-shadow: 0 0 11px #FFB302;;
    
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
