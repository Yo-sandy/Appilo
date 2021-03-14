<template>
<!--=====================================App ScreenShot Designed & Worked =====================================-->
<div class="container">
    <div class="row">
       <div class="text-center">
         <h2>App ScreenShots</h2>
         <p>A Private Limited is the most popular type of partnership Malta. The limited liability
           <br>
           is, in fact, the only type of company allowed by Companies.</p>
       </div>
    </div>
    <front-screenshot-swiper/>
   <div class="row" style="margin-top: 40px">
     <div class="col-md-5">
       <div style="padding-top: 50px">
         <h3>
           Designed & Worked
           <br>
           by the Latest Integration
         </h3>
         <p> A Private Limited is the most popular type of
           <br>
           partnership Malta. The limited liabilityis, in fact, the
           <br>
           only type of the company allowed by Companies.</p>
         <nuxt-link to="#" class="text-decoration-none discover">
           Discover
           <i class="fas fa-angle-right"></i>
         </nuxt-link>
       </div>
     </div>
     <div class="col-md-7">
       <div class="intigration-img-box text-right">
         <img src="/intigration-1-1-1-13-1-1-3-1.png" alt="">
         <img src="/intigration-1-2-1-13-1-1-3-1.png" alt="">
         <img src="/intigration-1-3-1-13-1-1-3-1.png" alt="">
         <img src="/intigration-1-4-1-13-1-1-3-1.png" alt="">
         <img src="/intigration-1-5-1-13-1-1-3-1.png" alt="">
       </div>
     </div>
   </div>
</div>
</template>

<script>
export default {
  name: "app-screenshot",
}
</script>

<style scoped>
/*===============Title Heading==============*/
h2{
  color: #170b35;
  font-size: 35px;
  font-weight: bold;
  line-height: 48px;
  margin-bottom: 20px;
}
h3{
  font-weight: 500;
  font-size: 35px;
  margin-top: 25px;
  margin-bottom: 20px;
}
p{
  margin-bottom: 1rem;
  font-size: 19px;
  color: grey;
}
.discover{
  font-weight: bold;
  color: #3d3dde;
  -webkit-background-clip: text;
}
.discover:hover{
  font-weight: bold;
  background: linear-gradient(to right,#6541c1 0,#d43396 98%,#d43396 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
/*===============Title Heading close==============*/


/*====================================================intigration-img-box=================================*/
 .intigration-img-box {
  position:relative;
  display:block;
  min-height:360px
}
 .intigration-img-box img {
  position:absolute;
  -webkit-transform:scale(1);
  transform:scale(1);
  -webkit-transition:all .4s ease;
  transition:all .4s ease;
  border-radius:20px
}
 .intigration-img-box img:hover {
  -webkit-transform:scale(1.02);
  transform:scale(1.02);
  -webkit-box-shadow:0 15px 30px rgba(212,50,151,.27);
  box-shadow:0 15px 30px rgba(212,50,151,.27)
}
 .intigration-img-box img:nth-child(1) {
  top:0;
  right:185px
}
 .intigration-img-box img:nth-child(2) {
  top:48px;
  right:60px
}
 .intigration-img-box img:nth-child(3) {
  top:170px;
  right:350px
}
 .intigration-img-box img:nth-child(4) {
  top:196px;
  right:200px
}
 .intigration-img-box img:nth-child(5) {
  bottom:0;
  right:0
}
/*====================================================intigration-img-box=================================*/


</style>
