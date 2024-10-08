<template>
  <div class="vid">
    <video src="@/assets/assets/Introducing iPhone 16 Pro _ Apple.mp4" autoplay   muted loop></video>
    <div class="posit">
      <!-- <img src="@/assets/assets/asset 16.png" alt="" height="50px"> -->
      <!-- <h5>You've never seen everything like this before</h5> -->
      <!-- <button class="more">learn more</button> -->
      <!-- <button class="buyy">Buy</button> -->
    </div>
  </div>

<div class="mac mt-1">
<h1>MacBook Air</h1>
<p>Lean.Mean.M3 machine</p>
<button class="learn">Learn More</button>
<button class="buy">Buy</button>
</div>

<div class="iphon mt-1">
<h1>Iphone</h1>
<p>Our most powerful cameras yet.</p>
<p>Ultrafast chips.And USB-C.</p>
<button class="learn">Learn More</button>
<button class="bsp">Shop Iphone</button>
</div>
<div>

<div class="m-2 d-flex gap-1">

  <div class="iph">
    <h2 class="pt-4">Iphone</h2>
    <h5>Our most powerful cameras yet.</h5>
    <h5>Ultrafast chips.And USB-C</h5>
    <button class="ble">Learn more</button>
    <button class="bsp">Shop iphone</button>
  </div>
  <div class="int">
    <h2 class="pt-4">Apple Intelligence</h2>
    <h5>Ai for  all of us.</h5>
    <h5>Coming in beta this fall</h5>
    <button class="ble">Learn more</button>
    <button class="bsp">Watch this film</button>
  </div>
</div>
<div class="m-2 d-flex gap-1">
  <div class="ipa">
    <h2 class="pt-4">Ipad Pro</h2>
    <h5>Unbelievably thin. incredibly powerful</h5>
    <h5>Coming in beta this fall</h5>
    <button class="ble">Learn more</button>
    <button class="buy">Buy</button>
  </div>

  <div class="wa">
    <h2 class="pt-4">Watch</h2>
    <h5>Series 9</h5>
    <h6>Smarter.Brighter.Migthier</h6>
    <button class="ble">Learn more</button>
    <button class="buy">Buy</button>
  </div>
</div>


<div class="m-2 d-flex gap-1">
  <div class="card">
    <center><img src="@/assets/assets/asset 19.png" alt="" width="100px" class="pt-4" ></center>
    <h5>Get up to 3% Daily cash back</h5>
    <h5>with every purchase</h5>
    <span>
      <button class="ble">Learn more</button>
      <button class="bsp">Apply now</button>
    </span>
  </div>

  <div class="Trade">
    <img src="@/assets/assets/asset 21.png" alt="" width="100px"  class="pt-4">
    <h5>Get $170-$620 in credit when you </h5>
    <h6>Trade in Iphone or higher.</h6>
    <button class="ble">Get your estimate</button>
  </div>
</div>

</div>

<div id="carouselExampleAutoplaying" class="carousel slide m-3 w-90" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="@/assets/assets/asset 24.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="@/assets/assets/asset 27.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="@/assets/assets/asset 29.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="@/assets/assets/asset 31.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="@/assets/assets/asset 33.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="@/assets/assets/asset 35.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="@/assets/assets/asset 37.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="@/assets/assets/asset 39.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="@/assets/assets/asset 41.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="@/assets/assets/asset 43.jpeg" class="d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>


<marquee behavior="" direction="">
<span><img src="" alt=""></span>
</marquee>
</template>
<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  *{
    margin: 0%;
    padding: 0%;
    outline: none;
  }
.mac{
  background: url(@/assets/assets/hero_macbook_air_m3__cp4t7pn8zqaa_large.jpg);
  width: 100%;
  height: 500px;
  background-repeat: no-repeat;
  background-position: center;
}
.iphon{
  background: url(@/assets/assets/asset0.png);
  width: 100%;
  height: 500px;
  background-repeat: no-repeat;
  background-position: center;
}
.iphon h1{
  color: rgb(255, 255, 255);
  font-size: 60px;
}
.iphon p{
  font-size: 30px;
  color: rgb(255, 255, 255);
}
.mac h1{
  color: black;
  font-size: 60px;
}
.mac p{
  font-size: 30px;
  color: black;
}
.learn{
  padding: 10px;
  font-size: 16px;
  /* width: 100px; */
  margin: 10px;
  background: rgb(0,113,227);
  border: none;
  color: white;
  border-radius: 20px;
}
.buy{
  border: 1px solid rgb(0,113,227);
  background: none;
  padding: 10px;
  width: 80px;
  font-size: 16px;
  color:rgb(0,113,227) ;
  border-radius: 20px;
}
.buy:hover{
background: rgb(0,113,227);
color: #ffffff;
}
.vid{
  /* position: absolute; */
}
.posit{
  bottom: 250px;
  position: relative;
  color: white;
}
.posit h5{
  font-size: 30px;
  font-weight:400;
}
.more{
  background: white;
  color: rgb(0, 0, 0);
  border: 2px solid white;
  border-radius: 30px;
  padding: 10px;
  font-size: 18px;
}
.buyy{
border: 1px solid white;
font-size: 18px;
color: white;
background: none;
height: 45px;
width: 80px;
margin: 10px;
border-radius: 20px;
}
.buyy:hover{
  background: white;
  color: black;
}
.vid video{
  width: 105.4%;
}
.iph{
  background: url(@/assets/assets/asset0.png);
  width: 50%;
  height: 500px;
  background-repeat: no-repeat;
  background-position: center;
}
.iph h2{
font-weight: 500;
font-size: 50px;
color: rgb(245,245,247);
}
.iph h5{
  color: rgb(245,245,247);
  font-weight: 400;
}
.int{
  background: url(@/assets/assets/asset15.png);
  width: 50%;
  height: 500px;
  background-repeat: no-repeat;
  background-position: center;
  color:black;
  
}
.ble{
  background: rgb(0,113,227);
  color: white;
  border-radius: 20px;
  height: 45px;
  padding: 10px;
  margin: 10px;
  border: none;
}
.bsp{
  border: 1px solid  rgb(0,113,227);
  color: rgb(0,113,227);
  background: none;
  height: 45px;
  border-radius: 20px ;
  padding: 10px;
  margin: 10px;
}
.int h2{
  font-weight: 500;
font-size:45px;
color: rgb(0, 0, 0);
}
.int h5{
  color: rgb(0, 0, 0);
  font-weight: 400;
}
.ipa{
  background: url(@/assets/assets/asset1.jpeg);
  width: 50%;
  height: 500px;
  background-repeat: no-repeat;
  background-position: center;
}
.ipa h2{
font-weight: 500;
font-size: 50px;
color: rgb(245,245,247);
}
.ipa h5{
  color: rgb(245,245,247);
  font-weight: 400;
}
.wa{
  background: url(@/assets/assets/promo_apple_watch_series_9_order__b3u85rm9zf6u_large.jpg);
  width: 50%;
  height: 500px;
  background-repeat: no-repeat;
  background-position: center;
}
.wa h2{
font-weight: 500;
font-size: 50px;
color: rgb(245, 245, 247);
}
.wa h6{
font-weight: 500;
font-size: 20px;
color: rgb(245, 245, 247);
}
.wa h5{
  color: rgb(255, 0, 0);
  font-weight: 400;
}
.card{
  background: url(@/assets/assets/asset20.jpeg);
  width: 50%;
  height: 500px;
  background-repeat: no-repeat;
  background-position: center;
}
/* .card h2{
font-weight: 500;
font-size: 50px;
color: rgb(245,245,247);
} */
.card h5{
  color: rgb(0, 0, 0);
  font-weight: 400;
}
.Trade{
  background: url(@/assets/assets/asset22.jpeg);
  width: 50%;
  height: 500px;
  background-repeat: no-repeat;
  background-position: center;
}
/* .card h2{
font-weight: 500;
font-size: 50px;
color: rgb(245,245,247);
} */
.Trade h5{
  color: rgb(0, 0, 0);
  font-weight: 400;
}
</style>
