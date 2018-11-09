<template>
  <div class="ChooseFarm">
    <div class="container">
      <div class="auc-title">เปิดประมูลสินค้า</div>
        <div class="container has-background-white roundcorner">
          
          <label>ฟาร์มที่เลือกเปิดทำการประมูล</label>
          <hr>
          <label>ฟาร์มที่เลือกเปิดทำการประมูล : </label>
          <a class="button yello">ถัดไป</a>
          <div class="card-container">
          <FarmBox farmname="Orange Farm" location="นครนายก, นครนายก" type="ส้ม" species="ORNG_001" area="100" amount="1,000" harvestable="950" date="14 กันยายน 2561"/>
          <FarmBox farmname="Orange Farm" location="นครนายก, นครนายก" type="ส้ม" species="ORNG_001" area="100" amount="1,000" harvestable="950" date="14 กันยายน 2561"/>
          <FarmBox farmname="Orange Farm" location="นครนายก, นครนายก" type="ส้ม" species="ORNG_001" area="100" amount="1,000" harvestable="950" date="14 กันยายน 2561"/>
          <FarmBox farmname="Orange Farm" location="นครนายก, นครนายก" type="ส้ม" species="ORNG_001" area="100" amount="1,000" harvestable="950" date="14 กันยายน 2561"/>
          <FarmBox farmname="Orange Farm" location="นครนายก, นครนายก" type="ส้ม" species="ORNG_001" area="100" amount="1,000" harvestable="950" date="14 กันยายน 2561"/>
          <FarmBox farmname="Orange Farm" location="นครนายก, นครนายก" type="ส้ม" species="ORNG_001" area="100" amount="1,000" harvestable="950" date="14 กันยายน 2561"/>
          </div>
          <a class="button yello-inv">ดูข้อมูลฟาร์มถัดไป</a>
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
  .farm-desc{
    padding: 0;
    margin-top: 5px;
    text-align: start;
  }
  .farm-name{
    font-size: 21px;
    font-weight: bold;
    color: #FFB302;
    text-align: start;
  }
  .roundcorner{
    border-radius: 3px;
  }
  label{
    font-weight: 600;
    text-align: start;
    justify-content: flex-start;
  }
  hr{
	border-top: 1px solid lightgray;
  margin-left: 1.5em;
  margin-right: 1.5em;
  margin-top:1em;
  margin-bottom: 1em;
  flex-basis: 100%;
}
.yello{
  background: #FFB302;
  color: white;
  font-size: 15px;
  font-weight: 200;
  width: 100px;
  height: 3em;
  border-radius: 5px;
}
.yello-inv{
  background: white ;
  color: #FFB302;
  font-size: 15px;
  font-weight: 200;
  width: 150px;
  height: 3.5em;
  border-radius: 5px;
  margin-bottom: 30px;
  border-color: #FFB302;
  margin-top: -15px;
}
.yello-inv:hover{
    box-shadow: 0 0 11px #FFB302;;
    color: #FFB302;
    
  }
</style>

