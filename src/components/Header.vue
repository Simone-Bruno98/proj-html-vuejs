<template>
<div class="row">
  <div class="header">
    <div class="whatsva">
      <div class="navigation">
        <img src="../assets/img/logo.png" alt="">
        <ul>
          <li>Home</li>
          <li>About</li>
          <li>Services</li>
          <li>Journal</li>
          <li>Contact</li>
        </ul>
      </div>
      <div class="buttons">
        <ul>
            <li class="phonenumber"><i class="bi bi-headphones"></i> 1.800.123.4567</li>
            <li class="navbutton">Get a free consultation</li>
        </ul>
      </div>
    </div>
    <div class="banner">
      <div class="bannertext">
        <h1>Indipendent professional who works remotely to help with your business.</h1>
        <p>Mauris aliquam libero, fermentum quis eros, masse sagittis. Lectus mattis elit purus venenatis.</p>
        <span class="button">What is VA exactly?</span>
      </div>
      <div class="bannerimage">
        <img src="../assets/img/info-5-400x444.jpg" alt="">
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.header{
    padding: 40px 10%;
    width: 100%;
    height: 750px;
    background-image: url(../assets/img/home-bg-3.svg), url(../assets/img/header-bg.svg);
    background-repeat: no-repeat;
    background-size: cover, contain;
    background-color: #0F1164;
}
.whatsva{
  display: flex;
  font-size: 17px;
  font-weight: 600;
  padding: 10px 5%;
  justify-content: space-between;
  color: white;
  ul{
  list-style-type: none;
  display: flex;
    li{
      padding: 10px 12px;
      margin: 0px 10px;
      
    }
  }
  .navigation{
    display:flex;
    justify-content: space-between;
    li{
      &:hover{
        border-bottom: 2px solid white
      }
    }
    img{
      height: 50px;
    }     
  }
  .navbutton{
      color: black;
      background-color: white;
      border-radius: 8px 8px;
      padding: 10px 30px;
      font-size: 17px;
      font-weight: 600;
      margin-left: 40px;
    }
}

.banner{
  display: flex;
  justify-content: space-around;
  padding: 20px 3%;
  .bannertext{
    text-align: center;
    width: 35%;
    color: white;
    font-weight: bld;
    h1{
      font-size: 60px;
      text-transform: bald;
      padding-top: 30px;
    }
    p{
      font-size: 25px;
      padding-top: 40px;
      margin-bottom: 60px;
    }
  }
  .bannerimage{
    width: auto;
    img{
      height: 600px;
      border-radius: 3%
    }
  }

}
</style>
