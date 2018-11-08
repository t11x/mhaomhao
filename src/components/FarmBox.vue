<template>
<!-- <h1>{{ msg }}</h1> -->
    <div class="farm-card">
      <div class="farm-pic"></div>
      <div class="farm-desc">
        <div class="farm-name">{{farmname}}<br></div>
        <label>{{location}}</label><br><br>
        <label>ผลไม้ : </label> {{type}} <br>
        <label>สายพันธุ์ : </label> {{species}}<br>
        <label>พื้นที่ (ไร่) : </label> {{area}} ไร่<br>
        <label>จำนวน (ต้น) : </label> {{amount}} ต้น<br>
        <label>ออก (ต้น) : </label> {{harvestable}} ต้น<br>
        <label>วันที่เก็บเกี่ยว : </label> {{date}}<br>
      </div>
    </div>
</template>

<script>
export default {
  name: 'FarmBox',
  props: {
     farmname: String,
     location: String,
     type: String,
     species: String,
     area: String,
     amount: String,
     harvestable: String,
     date: String,

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
    border-style: solid;
    border-width: 1px;
    border-color: lightgray;
    border-radius: 3px;
  }
  .farm-card:hover{
    box-shadow: 0 0 11px #FFB302;;
    
  }
  .farm-pic{
    position: relative;
    height: 250px;
    overflow: hidden;
    border-color: lightgray;
    border-style: solid;
    border-width: 1px;
  }
  .farm-desc{
    padding: 0;
    margin-top: 5px;
    text-align: start;
  }
  label{
    font-weight: 600;
    text-align: start;
  }
  .farm-name{
    font-size: 21px;
    font-weight: bold;
    color: #FFB302;
    text-align: start;
    
  }
</style>
