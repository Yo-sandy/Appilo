<template>
  <div class="container">
    <div class="row">
      <div class="content"style="overflow: hidden" >
        <div class="how-app-work-slider-wrapper">
          <div class="how-app-work-screen-mobile-image"></div>
          <div class="bx-wrapper" style="max-width: 100%">
            <div class="bx-viewport" >
              <ul class="transitions d-flex":style="{transform:` translate(${xAxis}px, 12px)`}">
                <li class="slider-item" v-for="(image, key) in images" :key="key">
                  <img :src="image" alt="">
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="text-center mt-md-4">
          <span class="swiper-btn-prev" @click="changeImage('left')">
            <i class="fas fa-angle-left"></i>
          </span>
      <span class="swiper-btn-next" @click="changeImage('right')">
            <i class="fas fa-angle-right"></i>
          </span>
    </div>
  </div>
</template>

<script>
export default {
  name: "screenshot-swiper",
  computed:{
    currentImage(){
      return this.images[this.image_position]
    }
  },
  data(){
    return{
      images:[
        "/slider-2-1-13-1-1-3-1.png",
        "/slider-1-1-13-1-1-3-1.png",
        "/slider-3-1-13-1-1-3-1.png",
        "/slider-2-1-13-1-1-3-1.png",
        "/slider-1-1-13-1-1-3-1.png",
        "/slider-3-1-13-1-1-3-1.png",
      ],
      image_position:0,
      xAxis:-614
    }
  },
  methods:{
    changeImage(value){

      let shift = 307;

      let imageFullWidth = shift  * (this.images.length-1);

      if(value === 'left'){
        if(this.xAxis !== 0){
          this.xAxis -= -shift;
        }else{
          this.xAxis = -imageFullWidth;
        }
      }
      else if (value === 'right'){
        if(this.xAxis !== -imageFullWidth){
          this.xAxis -= shift;
        }else{
          this.xAxis = 0;
        }
      }
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

.content{
  position: relative;
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
  margin-left:auto;
  margin-right:auto;
  border-radius:50px;
}
.how-app-work-screen-mobile-image {
  background-image:url("/iphone-moc-1-13-1-1-3-1.png");
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
  width: 100%;
  position: relative;
  height: 631px;
  -webkit-transform: translatez(0);
}
ul{
  margin-top: 0;
  margin-bottom: 0;
  position: relative;
  width: 100%;
  transition-duration: 800ms;
}
li{
  padding: 0;
  margin-top: 3px;
  margin-left: 6px;
  margin-right: 7px;
  float: left;
  list-style: outside none none;
  position: relative;
  width: 307px;
  left: -23px;

}
.bx-wrapper .slider-item img{
  border-radius: 50px;
}
.swiper-btn-prev{
  position: relative;
  font-size: 16px;
  color: #373a5b;
  width: 50px;
  height: 50px;
  line-height: 55px;
  text-align: center;
  border-radius: 50px;
  font-weight: 700;
  background-image: none;
  display: inline-block;
  margin: 0 15px;
  background-color: #e7ecf2;
  left: 10px;
  right: auto;
}
.swiper-btn-next{
  position: relative;
  font-size: 16px;
  color: #373a5b;
  width: 50px;
  height: 50px;
  line-height: 55px;
  text-align: center;
  border-radius: 50px;
  font-weight: 700;
  background-image: none;
  display: inline-block;
  margin: 0 15px;
  background-color: #e7ecf2;
  left: 10px;
  right: auto;
}
</style>
