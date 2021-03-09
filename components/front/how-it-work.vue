<template>
  <div class="container me-auto ms-auto" style="padding-top: 117px;max-width: 1140px">
      <div class="row">
          <div class="col-md-6 content" >
            <img src="/download-1.png" alt="" class="circled-img"/>
            <div class="how-app-work-slider-wrapper">
                <div class="how-app-work-screen-mobile-image"></div>
                <div class="bx-wrapper" style="max-width: 100%">
                     <div class="bx-viewport" style="overflow: hidden">
                          <ul class="transitions" :style="{transform:` translate(${xAxis}px, -4px)`}">
                              <li class="slider-item" v-for="(image, key) in images" :key="key">
                                <img :src="image" alt="" class="screnshot-img">
                              </li>
                          </ul>
                     </div>
                </div>
            </div>
          </div>
        <div class="col-md-6 app-item">
          <div class="how-app-work-content-wrap">
            <div class="title">
              <h3>How does this app work</h3>
            </div>
            <div class="how-app-work-content">
              <div @click="changeImage(0)" class="pager-item"  >
                <div class="single-how-app-work">
                  <div class="icon-box">
                    <div class="inner">
                      <i class="fas fa-laptop-code" ></i>
                    </div>
                  </div>
                  <div class="text-box">
                    <h4>Make a profile</h4>
                    <p>We use a customized application tobe
                      <br>
                      specifically designed a testing gnose
                      <br>
                      to keep away for people.
                    </p>
                  </div>
                </div>
              </div>
              <div @click="changeImage(1)" class="pager-item">
                <div class="single-how-app-work">
                  <div class="icon-box">
                    <div class="inner">
                      <i class="fas fa-cloud-download-alt"></i>
                    </div>
                  </div>
                  <div class="text-box">
                    <h4>Download it for Free</h4>
                    <p>We use a customized application tobe
                      <br>
                      specifically designed a testing gnose
                      <br>
                      to keep away for people.
                    </p>
                  </div>
                </div>
              </div>
              <div @click="changeImage(2)" class="pager-item">
                <div class="single-how-app-work">
                  <div class="icon-box">
                    <div class="inner">
                      <i class="fas fa-shield-alt"></i>
                    </div>
                  </div>
                  <div class="text-box">
                    <h4>Enjoy this App</h4>
                    <p>We use a customized application tobe
                      <br>
                      specifically designed a testing gnose
                      <br>
                      to keep away for people.
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <nuxt-link to="#" class="download-btn active text-decoration-none me-md-3">
              <i class="fab fa-apple"></i>
              <span class="inner">
              <span class="avail">Available On</span>
              <span class="store-name">APP STORE</span>
            </span>
            </nuxt-link>
            <nuxt-link to="#" class="download-btn text-decoration-none">
              <i class="fab fa-google-play"></i>
              <span class="inner">
              <span class="avail">Available On</span>
              <span class="store-name">APP STORE</span>
            </span>
            </nuxt-link>
          </div>
        </div>
      </div>
    <front-how-it-work-2/>
  </div>
</template>
circled-img
<script>
export default {
name: "how-it-work",
  computed:{
    currentImage(){
      return this.images[this.image_position]
    }
  },
  data(){
    return{
      images:[
        "/slider-1-1-13-1-1-3-1.png",
        "/slider-2-1-13-1-1-3-1.png",
        "/slider-3-1-13-1-1-3-1.png",
      ],
      image_position:0,
      xAxis:0
    }
  },
  methods:{
    changeImage(value){
      let that = this;
      this.image_position = value;

      let currentXAxis = that.xAxis;
      let desireXAxis = 0;

      if (value ===0){
        desireXAxis = 0
      }
      else if(value ===1) {
        desireXAxis = -307
      }
      else if(value ===2) {
        desireXAxis = -614
      }
      let interval = setInterval(function () {
        if (desireXAxis === that.xAxis){
          clearInterval(interval);
        }else{
           if(currentXAxis <= -614 || value ===0){
             that.xAxis += 76.75;
           } else{
             that.xAxis -=76.75;
           }
        }
      }, 36);
    }
  }
}
</script>

<style scoped>

.fade-enter-active,
.fade-leave-active {
  transition: all 0.9s ease;
}

.fade-enter,
.fade-leave-to {
  opacity: 0;
}

/* =============================================== col-6-1 start ================*/
 .content{
   position: relative;
 }
.content img.circled-img{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
}
.circled-img{
  height: auto;
  max-width: 100%;
  border: none;
  box-shadow: none;
}

.how-app-work-slider-wrapper {
  position:relative;
  width:305px;
  height:655px;
  overflow:hidden;
  margin-left:auto;
  margin-right:auto;
  border-radius:50px;
  -webkit-box-shadow:0 18px 37px rgba(212,50,151,.2);
  box-shadow:0 18px 37px rgba(212,50,151,.2)
}
.how-app-work-screen-mobile-image {
  background-image:url("/fature-png-phone.png");
  background-repeat:no-repeat;
  background-size:100% 100%;
  display:block;
  height:655px;
  left:calc(50% + .5px);
  position:absolute;
  top:0;
  -webkit-transform:translateX(-50%);
  transform:translateX(-50%);
  width:310px;
  z-index:1
}
.bx-wrapper{
  border: 0;
  -webkit-box-shadow:none;
  box-shadow:none;
  border-radius:50px
}
.bx-viewport{
  overflow: visible!important;
  width: 100%;
  position: relative;
  height: 631px;
  -webkit-transform: translatez(0);
}
ul{
  margin-top: 0;
  margin-bottom: 1rem;
  width: 3215%;
  position: relative;
  transition-duration: 0s;
}
li{
  padding: 0;
  margin: 0;
  float: left;
  list-style: outside none none;
  position: relative;
  width: 307px;
  left: -35px;

}
.bx-wrapper .slider-item{
  text-align: center;
}
.bx-wrapper .slider-item img{
  margin-right: auto;
  margin-left: auto;
  border-radius: 50px;
}
.screnshot-img{
  margin-left: auto;
  margin-right: auto;
  border-radius: 50px;
}
.bx-wrapper img{
  display: block;
}
/* ============================================== col-6-1 close================*/

/*more btn*/

</style>
