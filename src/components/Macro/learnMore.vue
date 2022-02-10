<template>
  <div class="list">
    
    <div class="top">
      <div class="row">
        <p>Donec est tristique eu massa pellentesque.</p>
        <h2>Highly-skilled, independent professional freelancer.</h2>
      </div>
    </div>
    <span class="button">What is VA exactly?</span>
    <div class="bottom">
      <div class="row justify-content-evenly">
        <div class="col-3 d-flex">
          <div class="col-4">
            <span class="number">1.</span>
          </div>
          <div class="col-8">
            <p>Pellentesque pellentesque montes, pellentesque rutrum enim nisi purus posuere senectus.</p>
            <p class="redtext">Learn More</p>
          </div>
        </div>
        <div class="col-3 d-flex">
          <div class="col-4">
            <span class="number">2.</span>
          </div>
          <div class="col-8">
            <p>Pellentesque pellentesque montes, pellentesque rutrum enim nisi purus posuere senectus.</p>
            <p class="redtext">Learn More</p>
          </div>
        </div>
        <div class="col-3 d-flex">
          <div class="col-4">
            <span class="number">3.</span>
          </div>
          <div class="col-8">
            <p>Pellentesque pellentesque montes, pellentesque rutrum enim nisi purus posuere senectus.</p>
            <p class="redtext">Learn More</p>
          </div>
        </div>
      </div>
    </div>
   
  </div>
</template>

<script>
export default {
  name: 'learnMore',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.list{
  background-image: url(../../assets/img/info-bg-3.svg);
  background-repeat: no-repeat;
  background-size: 1500px;
  background-position: bottom left;
  width: 100%;
  height: 900px;
  margin-top: 150px;
  background-color: #0D1267;
  color: white;
  text-align: center;
  padding: 0% 15%;
  padding-top: 100px;
  
  .top{
    .row{
      p{

      }
      h2{
        font-size: 40px;
        padding: 0 35%;
        margin-bottom: 70px;
      }
    }
  }
  .bottom{
    margin-top: 100px;

    .row{
      .col-3{
        p{
        font-size: 18px;
        text-align: left;
        }
        span{
          font-size: 45px;
          
        }
        background-color: #000545 ;
        height: 300px;
        width: 400px;
        padding: 60px 20px;
        border-radius: 10px 10px;
        
      }
      
    }
  }
  .redtext{
    color:red;
    text-decoration: underline;
    padding-top: 30px;
  }
}
.button{
  background-color: #f36137;
  color: white;
}

</style>