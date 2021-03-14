<template>
  <div class="row section">
      <div class="col-md-6 tool-6">
        <div style="padding-top: 50px">
          <i class="fas fa-tools tool-icon"></i>
          <h3>
            Easy to Manage Your All Data
            <br>
            by This App
          </h3>
          <p>In order to design a mobile app that is going to be module
            <br>
            downloaded and accessed frequently by users, you need
            <br>
            offer an experience that isn’t available elsewhere. Often
            <br>
            businesses get caught up.</p>
          <nuxt-link to="#" class="text-decoration-none discover">
            Discover
            <i class="fas fa-angle-right"></i>
          </nuxt-link>
        </div>
      </div>
      <div class="col-md-6" style="padding-bottom: 117px">
        <img src="/data-moc-1-13-1-1-3-1.png" alt="" class="data-moc-img">
      </div>
      <div class="col-md-6">
        <img src="/responsive-moc-13-2-1-3-1(1).png" alt="" class="responsive-moc-img">
      </div>
      <div class="col-md-6 tool-6">
        <div style="padding-top: 50px">
          <i class="fas fa-laptop-code tool-icon" ></i>
          <h3>
            Responsive Design for All
            <br>
            Devices with Quality
          </h3>
          <p>In order to design a mobile app that is going to be module
            <br>
            downloaded and accessed frequently by users, you need
            <br>
            offer an experience that isn’t available elsewhere. Often
            <br>
            businesses get caught up.</p>
          <nuxt-link to="#" class="text-decoration-none discover">
            Discover
            <i class="fas fa-angle-right"></i>
          </nuxt-link>
        </div>
      </div>
      <div class="appilo-video-box">
          <div class="container text-center">
              <h3>Watch a Quick Tutorial</h3>
              <nuxt-link to="#" class="video-popup video-btn hvr-pulse">
                <i class="fas fa-play"></i>
              </nuxt-link>
          </div>
      </div>
    </div>
</template>

<script>
export default {
name: "how-it-work-2"
}
</script>

<style scoped>
.section{
  padding: 107px 0 117px;
}
/* tool-6*/
.tool-6{
}
.tool-icon{
  font-size: 45px;
  background: linear-gradient(to right,#6541c1 0,#d43396 98%,#d43396 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  line-height: 1;
}
h3{
  font-weight: 500;
  font-size: 35px;
  margin-top: 25px;
  margin-bottom: 20px;
}
p{
  margin-bottom: 20px;
  color: grey;
  font-size: 19px;
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
.data-moc-img{
  border: none;
  border-radius: 0;
  box-shadow: 0 16px 43px rgba(78,48,135,.24);
  vertical-align: middle;
}
.responsive-moc-img{
  width: 545px;
  height: 465px;
}
.appilo-video-box {
  background:#d9378b url('/video-bg-1-13-1-1-3-1.jpg') center center no-repeat fixed;
  background-size:cover;
  position:relative;
  padding:126px 0
}
.appilo-video-box:before {
  content:'';
  position:absolute;
  top:0;
  left:0;
  right:0;
  bottom:0;
  background:rgba(61,30,130,.67)
}
.appilo-video-box .container {
  position:relative
}
.appilo-video-box h3 {
  margin:0;
  color:#fff;
  font-weight:600;
  font-size:32px;
  margin-bottom:50px
}
.appilo-video-box a{
  width:109px;
  height:109px;
  border-radius:50%;
  background:rgba(255,255,255,.3);
  text-align:center;
  display:inline-block;
  line-height:109px;
  -webkit-animation-name:hvr-pulse;
  animation-name:hvr-pulse;
  -webkit-animation-duration:1s;
  animation-duration:1s;
  -webkit-animation-timing-function:linear;
  animation-timing-function:linear;
  -webkit-animation-iteration-count:infinite;
  animation-iteration-count:infinite
}
.appilo-video-box a.video-btn i {
  display:inline-block;
  vertical-align:middle;
  width:84px;
  height:84px;
  color:#fff;
  font-size:20px;
  line-height:84px;
  border-radius:50%;
  background:#d9378b
}

@keyframes hvr-pulse {
  25% {
    -webkit-transform:scale(1.1);
    transform:scale(1.1)
  }
  75% {
    -webkit-transform:scale(.9);
    transform:scale(.9)
  }
}

/* tool-6 close*/
</style>
