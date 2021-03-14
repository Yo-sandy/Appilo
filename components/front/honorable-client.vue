<template>
<div class="appilo-main-testimonial  testimonials-style-one">
  <div class="container">
    <div class="title" >
       <div class="row">
         <div class="col-md-5"></div>
           <div class="col-md-7">
             <h3>Some Talk of Our
               <br>
               Honorable Clients
             </h3>
           </div>
       </div>
    </div>
   <div class="position-relative" style="top:-182px">
     <div id="#testimonials-slider-pager" class="testimonials-slider-pager-all">
       <nuxt-link to="#" class="pager-item"><img src="/testi-1-1-1-13-1-1-3-1.png"></nuxt-link>
       <nuxt-link to="#" class="pager-item"><img src="/testi-1-2-13-1-1-3-1.png"></nuxt-link>
       <nuxt-link to="#" class="pager-item"><img src="/testi-1-3-13-1-1-3-1.png"></nuxt-link>
       <nuxt-link to="#" class="pager-item"><img src="/testi-1-4-13-1-1-3-1.png"></nuxt-link>
       <nuxt-link to="#" class="pager-item"><img src="/testi-1-1-1-13-1-1-3-1.png"></nuxt-link>
       <nuxt-link to="#" class="pager-item"><img src="/testi-1-2-13-1-1-3-1.png"></nuxt-link>
     </div>
     <div class="testimonials-slider">
       <div class="bx-wrapper" style="max-width: 100%">
         <div class="bx-viewport">
           <ul class="slider" style="width: auto; position: relative">
             <li class="slide-item">
               <div class="single-testimonial">
                 <div class="img-box position-absolute" style="bottom: -90%; left: 20%; transform: translate(-45%, -20%);">
                   <img src="/testi-1-1-1-13-1-1-3-1.png" style="height: auto;width: auto">
                 </div>
                   <div class="text-box" style="position: relative;left: 47%;top: 200px!important;">
                     <p>The number of ICOs being launched is increasing every day.
                       <br>
                       The right team can help your ICO stand out from the crowd.
                       <br>
                       We're that team.</p>
                     <h3>Jhon</h3>
                     <span>CEO</span>
                   </div>
                 </div>
             </li>
           </ul>
         </div>
         <div class="text-center mt-md-4">
          <nuxt-link to="#" class="bx-prev me-md-3" >
            <i class="fas fa-long-arrow-alt-left"></i>
          </nuxt-link>
           <nuxt-link to="#" class="bx-next"  >
             <i class="fas fa-long-arrow-alt-right"></i>
          </nuxt-link>
         </div>
       </div>
     </div>
   </div>
  </div>
</div>
</template>

<script>
export default {
name: "honorable-client"
}
</script>

<style scoped>
*{
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
}
.container {
  max-width: 970px;
  padding: 49px 0 0;
  position: relative;
}
.testimonials-style-one .title{
  margin-bottom: 15px;
}
.row{
  display: flex;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
}
.col-md-5{
  flex: 0 0 41.666667%;
  max-width: 41.666667%;
  width: 100%;
  position: relative;
  padding-left: 15px;
  padding-right: 15px;
}
.testimonials-style-one .title h3 {
  color: #170b35;
  font-size: 32px;
  line-height: 48px;
  font-weight: bold;
  padding-left: 35px;
}
.col-md-7{
  flex: 0 0 58.333333%;
  max-width: 58.333333%;
  position: relative;
  width: 100%;
  min-height: 1px;
  padding-right: 15px;
  padding-left: 15px;
}
  a img {
  max-width:70px;
  max-height:70px
}
 .pager-item {
  position:absolute;
  top:0;
  left:0;
}
 a.pager-item:nth-child(1) {
  top:90%;
  left:30%
}
 a.pager-item:nth-child(2) {
  top:85%;
  left:18%
}
 a.pager-item:nth-child(3) {
  top:70%;
  left:2%
}
 a.pager-item:nth-child(4) {
  top:36%;
  left:0
}
 a.pager-item:nth-child(5) {
  top:9%;
  left:8%
}
 a.pager-item:nth-child(6) {
  top:2%;
  left:25%
}
@media(max-width:768px) {
   .testimonials-slider-pager-all {
    display:none
  }
}
/*=============================================testimonials-slider======================*/
.testimonials-slider .bx-wrapper {
  border:0;
  -webkit-box-shadow:none;
  box-shadow:none;
  background-color:transparent;
  margin-bottom:0
}
.bx-wrapper{
  position: relative;
  margin: 0 auto 60px;
  touch-action: pan-y;
}
.bx-viewport {
  width: 100%;
  overflow: hidden;
  position: relative;
  height: 400px;
  -webkit-transform:translatez(0);
  box-sizing: border-box;
}
li{
  float: none;
  list-style: outside none none;
  position: absolute;
  width: 970px;
  display: block;
}
.single-testimonial{
  padding-top: 10px;
}
.single-testimonial .img-box{
  width: 450px;
  display: table-cell;
  vertical-align: top;
}
.single-testimonial .img-box img{
  max-width: none;
  width: auto;
  margin-left: auto;
  margin-right: auto;
  position: relative;
  top: 18px;
  box-shadow: 0 15px 33.6px rgba(212,50,151,.3);
  border-radius: 50%;
}
.bx-wrapper img{
  display: block;
}
.single-testimonial .text-box p {
  font-size: 18px;
  color: #656565;
  line-height: 26px;
  letter-spacing: .01em;
  margin-top: 25px;
  margin-bottom: 20px;
}
.single-testimonial .text-box h3 {
  color: #170b35;
  font-size: 20px;
  font-weight: 500;
  margin-bottom: 10px;
}
.single-testimonial .text-box span {
  color: #6b40bf;
  font-size: 16px;
}
.bx-prev{
  text-indent: 0;
  background-image: none;
  color: #6b40bf;
  font-size: 27px;
  position: relative;
  top: 10px;
}
.bx-next{
  text-indent: 0;
  background-image: none;
  color: #6b40bf;
  font-size: 27px;
  position: relative;
  top: 10px;
}
</style>
