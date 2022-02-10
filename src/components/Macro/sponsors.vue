<template>
  <div class="sponsors">
    <span class="redtext d-flex justify-content-center">Trusted by these amazing brands</span>
    <div class="row justify-content-center align-items-center">
      <div class="col-2">
        <img src="../../assets/img/brand-1.jpg" alt="">
      </div>
      <div class="col-2">
        <img src="../../assets/img/brand-3.jpg" alt="">
      </div>
      <div class="col-2">
        <img src="../../assets/img/brand-4.jpg" alt="">
      </div>
      <div class="col-2">
        <img src="../../assets/img/brand-5.jpg" alt="">
      </div>
      <div class="col-2">
        <img src="../../assets/img/brand-7.jpg" alt="">
      </div>
    </div>
    <div class="row text-image justify-content-center">
      <div class="col-6 text align-self-middle">
        <img src="../../assets/img/icon-2-2x.png" alt="">
        <h3>Professional who works to help with your business.</h3>
        <p>Donec est tristique eu massa pellentesque non sit sit donec. Prein auctor est vehicula.</p>
        <span class="button">What is VA exactly?</span>
      </div>
      <div class="col-6 image d-flex justify-content-center">
        <img src="../../assets/img/info-5-2x-800x864.png" alt="">
      </div>
    </div>
    <div class="row list justify-content-evenly">
        <div class="col-3  first d-flex">
          <div class="col-4">
            <span class="number">1.</span>
          </div>
          <div class="col-8">
            <p class="title">Learn to delegate</p>
            <p>Pellentesque pellentesque montes, pellentesque rutrum enim nisi purus posuere senectus. Cros ultricies ligula sed maga dictum porta. Lorem ipsum dolor sit amet.</p>
            <p class="redtext">Learn More</p>
          </div>
        </div>
        <div class="col-3  second d-flex">
          <div class="col-4">
            <span class="number">2.</span>
          </div>
          <div class="col-8">
            <p class="title">Reduce labor costs</p>
            <p>Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; donee velit neque, auctior sit amet aliquam vel, ullamorcorporer.</p>
            <p class="redtext">Learn More</p>
          </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'sponsors',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .sponsors{
    width: 100%;
    padding: 0% 15%;
    .col-2{
      img{
        width: 100%;
      }
    }
  .text-image{
    margin-top: 80px;
  .text{
    text-align: center;
    color: #0D146A;
    padding: 0px 8%;
    align-self: center;
    h3{
      font-size: 40px;
    }
    p{
      font-size: 20px;
      margin-bottom: 60px;
    }
    
  }
}
.row{
  margin-top: 100px;
  .col-3{
    color: white;
    .title{
      font-size:20px ;
      
    }
    p{
    font-size: 15px;
    text-align: left;
    }
    span{
      font-size: 40px;
      
    }
    background-color: #000545 ;
    height: 250px;
    width: 600px;
    padding-top: 30px;
    border-radius: 10px 10px;        
  }
  .number{    
    padding-left: 30px;
  }
}
.image{ 
  img{
    width: 80%;
  }
}
  }
  .redtext{
    color: red;
    margin-top: 70px;
    margin-bottom: 30px;
  }
.button{
  background-color: #f36137;
  color: white;
}
.first{
  background-image: url(../../assets/img/box-bg-1.svg);
  background-size: contain;
  background-repeat: no-repeat;
  background-position: left ;
}
.second{
  background-image: url(../../assets/img/box-bg-2.svg);
  background-size: contain;
  background-repeat: no-repeat;
  background-position: right ;
}
</style>