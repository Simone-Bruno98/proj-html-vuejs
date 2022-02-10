<template>
  <div class="whatsva">
      <div class="navigation">
        <img src="../../assets/img/logo.png" alt="">
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
</template>

<script>
export default {
  name: 'WhatsVA',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
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
</style>