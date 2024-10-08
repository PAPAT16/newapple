<template>
  <div class="d-flex p-4 gap-4 justify-content-center">
    <p>Choose another country or region to see content specific to your location.</p>
    <select name="" id="" class="w-reg">
      <option value="">Nigeria</option>
      <option value="">Nigeria</option>
      <option value="">Nigeria</option>
      <option value="">Nigeria</option>
      <option value="">Nigeria</option>
    </select>
    <button class="cont">Continue</button>
  </div>
  <!-- navbar begins -->
  <nav class="navbar navbar-expand-md">
    <div class="container">
      <router-link to="/"><a class="navbar-brand"><i class="bi bi-apple"></i></a></router-link>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse " id="navbarSupportedContent">
      <ul class="navbar-nav gap-3 ">
        <li class="nav-item dropdown"><router-link to="/store" class="nav-link dropdown"   >Store</router-link> 
          <div class="dropdown-menu">
                      <ul>
            <p class="shop m-0">Shop</p>
            <li><a class="dropdown-item" href="#">Shop the latest</a></li>
            <li><a class="dropdown-item" href="#">Mac</a></li>
            <li><a class="dropdown-item" href="#">Ipad</a></li>
            <li><a class="dropdown-item" href="#">Iphone</a></li>
            <li><a class="dropdown-item" href="#">Apple Watch</a></li>
            <li><a class="dropdown-item" href="#">Apple Vision Pro</a></li>
            <li><a class="dropdown-item" href="#">Accesories</a></li>
          </ul>
            <ul>
              <p class="shop m-0">Quick links</p>
              <li><a class="dropdown-item" href="#">Shop the latest</a></li>
            <li><a class="dropdown-item" href="#">Mac</a></li>
            <li><a class="dropdown-item" href="#">Ipad</a></li>
            </ul>
          </div>
        </li>
        <li class="nav-item"><router-link to="/about" class="nav-link">Mac</router-link></li>
        <li class="nav-item"><router-link to="" class="nav-link">Ipad</router-link></li>
        <li class="nav-item"><router-link to="" class="nav-link">Iphone</router-link></li>
        <li class="nav-item"><router-link to="" class="nav-link">Watch</router-link></li>
        <li class="nav-item"><router-link to="" class="nav-link">Vision</router-link></li>
        <li class="nav-item"><router-link to="" class="nav-link">Airpods</router-link></li>
        <li class="nav-item"><router-link to="" class="nav-link">Tv & Home</router-link></li>
        <li class="nav-item"><router-link to="" class="nav-link">Entertainment</router-link></li>
        <li class="nav-item"><router-link to="" class="nav-link">Accesories</router-link></li>
        <li class="nav-item"><router-link to="" class="nav-link">Support</router-link></li>
        <li class="nav-item"><i class="bi bi-search"></i></li>
        <li class="nav-item"><i class="bi bi-bag"></i></li>
      </ul>
    </div>
  </div>
  </nav>
  <router-view/>
  <!-- navbar ends -->
   <footerbottomvue/>
</template>
<script>
import footerbottomvue from '@/components/footerbottom.vue'
import HelloWorld from './components/HelloWorld.vue';
export default{
 components:{
  footerbottomvue,
  HelloWorld
 }
}
</script>
<style>
.cont{
  background: black;
  border: none;
  color: white;
  border-radius: 10px;
}
.w-reg{
  width: 200px;
  border-radius: 10px;
  border: none;
  background: rgb(240,240,242);
}
#app {
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  overflow-x: hidden;
  color: #2c3e50;
}
/* nav a.router-link-exact-active {
  color: rgb(199,199,200);
} */
.nav-link{
  font-size: 12px;
  font-weight: 400;
  line-height: 12px;
  font-style: normal;
  color:rgb(0, 0, 0);
}
.nav-link:hover{
    color: rgb(0, 0, 0);
}
.navbar{
  background:rgb(246,246,248);
  /* filter: blur(0.5px) brightness(120%) saturate(5%) */
/* padding-left: 200px;
padding-right: 50px; */
/* filter: blur(0.5px) ; */
}
.navbar-brand{
color: rgb(0, 0, 0);
}
.navbar-brand:hover{
  color: rgb(0, 0, 0);
}
.nav-item i{
  color:rgb(0, 0, 0);
}

.navbar-nav .dropdown:hover .dropdown-menu {
            display: block;
            position: absolute;
            width: 100vw;
            left: 0;
            right: 0;
            top: 100%;
            background:rgb(29,29,31);
        }

        .dropdown-menu {
            border-radius: 0;
            margin: 0;
            padding: 0;
            transform: translateX(-120px);
            transition-delay: 0.3s;
            border: none;
        }

.dropdown-item{
  color: rgb(149, 149, 149);
  padding: 5px ;
}
.dropdown-menu .dropdown-item{
  font-size: 20px;
  padding-left: 50px;
  font-weight: 600;
}
.shop{
  padding-left: 50px;
  color: rgb(75, 73, 73);
  font-size: 13px;
}
.dropdown-item:hover{
  background: none;
  color: rgb(189, 189, 189);
}
.dropdown-menu ul{
  list-style: none;
}
</style>
