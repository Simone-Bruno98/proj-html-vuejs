<template>
  <div class="services">
    <div class="redtext">Available services</div>
    <div class="row list justify-content-center">
      <div class="col-2">
        <h2>Answering phone calls</h2>
        <p>Elementrum posuere mauris, ac ultricies eu orci massa at id tincidunt.</p>
      </div>
      <div class="col-2 center">
        <h2>Basic data entry</h2>
        <p>Accumsan odio id nec mauris, eu tortor at. Vitae tincidunt enim quis.</p>
      </div>
      <div class="col-2 center">
        <h2>Organizing calendar</h2>
        <p>Elementum blandit erat odio quam pellentesque aliquam faucibus.</p>
      </div>
      <div class="col-2">
        <h2>Booking travels</h2>
        <p>Est dignissim ipsum tellus, hendreirit ac aliquam eu val blandit ac amet ut ut.</p>
      </div>
    </div>
    <div class="row whatisva justify-content-center">
      <div class="col-6 image d-flex justify-content-center">
        <img src="../../assets/img/info-5-2x-800x864.png" alt="">
      </div>
      <div class="col-6 text align-self-middle">
        <img src="../../assets/img/icon-1-2x-200x155.png" alt="">
        <h3>Find the ultimate virtual assistant for your business</h3>
        <p>Donec est tristique eu massa pellentesque non sit sit donec. Pronin auctor est vehicula</p>
        <span class="button">What is VA exactly?</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'availableServices',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.services{
  height: 900px;
      padding: 0% 15%;
}
.redtext{
  color: red;
  font-weight: 600;
  margin-top: 60px;
  margin-bottom: 30px;
}
.center{
      border-left: 2px solid #D7B2A9;
      border-right: 2px solid #D7B2A9;
    }
.list{
  border-top: 2px solid #D7B2A9;
  width: 100%;
  margin: 0 auto;
  margin-bottom: 100px;
  color: #0D146A;
  .col-2{
    border-top: 2px solid #D7B2A9;
    width: 25%;
    padding: 3% 7%;
    h2{
      text-align: start;
    }
  }
}
.whatisva{
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
.image{ 
  
  img{
    width: 80%;
  }
}
.button{

  background-color: #f36137;
  color: white;
}
</style>