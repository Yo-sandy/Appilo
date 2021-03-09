<template>
  <div class="section row">
    <div class="col-lg-6 col-md-12 item-1">
     <div style="padding-top: 140px" class="me-5">
       <h3>Awesome App for Your Modern Lifestyle</h3>
       <p>Increase productivity with a simple to-do app. app for
         managing your personal budgets</p>

        <nuxt-link to="#" class="text-decoration-none download-app me-md-3">Download App</nuxt-link>
       <nuxt-link to="#" class="slider-btn appilo-thm-btn borderd text-decoration-none"><span>Discover More</span></nuxt-link>
     </div>
    </div>
    <div class="col-lg-6 col-md-12 item-1" style="position: relative; left: 120px">
      <div >
        <img src="/slider-moc-2-1.png" class="img-tag"/>
      </div>
    </div>
    <div class="container">
        <div class="row all-counter">
          <div class="col-lg-3 col-md-6 col-sm-6 text-center">
            <p class="fun-fact"><span class="counter">1,265</span>Users</p>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-6">
            <p class="fun-fact"><span class="counter">1,000</span>Download</p>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-6">
            <p class="fun-fact"><span class="counter">508</span>Like</p>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-6">
            <p class="fun-fact"><span class="counter">809</span>5 star Rating</p>
          </div>
        </div>
    </div>
    <div class="separator"></div>
  </div>
</template>

<script>
export default {
  name: "home"
}
</script>

<style scoped>

/*Section Row*/
.section{
  padding-top: 190px;
  overflow: hidden;
}
.row{
  margin-right: -15px;
  margin-left: -15px;
}
.item-1{
  min-height: 1px;
  padding-right: 15px;
  padding-left: 15px;
}
h3{
  color: #190a32;
  font-size: 42px;
  line-height: 60px;
  font-weight: bold;
  margin-bottom: 11px;
}
p{
  color: #666;
  font-size: 16px;
  line-height: 30px;
  margin-bottom: 54px;
}
.img-tag{
  float: right!important;
  left: 175px;
}

/*download app*/

.download-app{
  box-shadow: 0 5px 30px rgba(212,50,151,.2), 0 5px 8px rgba(212,50,151,.5);
  display: inline-block;
  background: linear-gradient(to right,#6541c1 0,#d43396 98%,#d43396 100%);
  color: #fff;
  font-size: 16px;
  font-weight: 600;
  transition: all .4s ease;
  border-radius: 28px;
  padding: 15px 29px;
  position: relative;
  cursor: pointer;
}
/*download app close*/

/*!*download more*!*/
.appilo-thm-btn {
  display:inline-block;
  border:0;
  outline:0;
  background:#6541c1;
  background:-webkit-gradient(linear,left top,right top,from(#6541c1),color-stop(98%,#d43396),to(#d43396));
  background:linear-gradient(to right,#6541c1 0,#d43396 98%,#d43396 100%);
  filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#6541c1',endColorstr='#d43396',GradientType=1);
  color:#fff;
  font-size:16px;
  font-weight:600;
  -webkit-transition:all .4s ease;
  transition:all .4s ease;
  border-radius:28px;
  padding:15px 29px;
  position:relative
}
.appilo-thm-btn:before {
  content:'';
  position:absolute;
  top:2px;
  left:2px;
  right:2px;
  bottom:2px;
  border-radius:28px;
  background:#fff;
  opacity:0;
  -webkit-transition:all .4s ease;
  transition:all .4s ease
}
.appilo-thm-btn:hover {
  color:#190a32
}
.appilo-thm-btn:hover:before {
  opacity:1
}
.appilo-thm-btn>span {
  position:relative
}
.appilo-thm-btn.borderd {
  color:#190a32
}
.appilo-thm-btn.borderd:before {
  content:'';
  position:absolute;
  top:2px;
  left:2px;
  right:2px;
  bottom:2px;
  border-radius:28px;
  background:#fff;
  opacity:1;
  -webkit-transition:all .4s ease;
  transition:all .4s ease
}
.appilo-thm-btn.borderd:hover {
  color:#fff
}
.appilo-thm-btn.borderd:hover:before {
  opacity:0
}
/*download more close*/

/* user like rating*/
.all-counter{
  justify-content: center !important;
}
.counter{
  background: linear-gradient(to right,#6541c1 0,#d43396 98%,#d43396 100%);
  background-clip: border-box;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: 200 !important;
  font-size: 53px;
}
.fun-fact{
  color: #656565;
  font-size: 20px;
  font-weight: bold;
  margin: 0;
}
.separator{
  display: block;
  width: 100%;
  margin-left: auto;
  margin-right: auto;
  height: 1px;
  background: rgba(83,82,83,.15);
  margin-top: 70px;
}
/* user like rating close*/
/*Section Row Close*/

</style>
