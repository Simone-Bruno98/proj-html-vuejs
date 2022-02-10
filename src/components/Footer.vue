<template>
  <div class="Footer">
   <WhatsVA/>
   <div class="row">
     <div class="col-6">
        <h2>Indipendent professional who works remotely to help with your business.</h2>
        <span class="button">What is VA exactly?</span>
        <p>© Copyright 2012 - 2020 | Avada Theme by <span class="coloredtext">ThemeFusion</span> | All Rights Reserved | Powered by <span class="coloredtext">WordPress</span></p>
     </div>
   </div>
   
  </div>
</template>

<script>
import WhatsVA from './Macro/WhatsVA.vue'
export default {
  name: 'Footer',
  components: {
    WhatsVA
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.Footer{
  margin-top: 100px;
  height: 550px;
  padding: 0% 15%;
  padding-top: 60px;
  background-color: #0D1267;
  background-image: url(../assets/img/footer-bg-1.svg);
  background-repeat: no-repeat;
  background-size: cover;
  .col-6{
    padding: 0% 6%;
    color: white;
    h2{
      font-size: 40px;
      margin-bottom: 50px;
    }
    span{
      margin-top: 100px;
    }
    p{
      margin-top: 50px;
    }
  }
}
</style>
