<template>
      <div class="container">
          <div class="row">
            <div class="col-md-3 col-sm-6 col-xs-12">
              <nuxt-link to="#"><img src="/logo-appilo.png" alt=""></nuxt-link>
              <p class="appilo-title">Be the first to find out about exclusive deals, the latest Lookbooks trends.
                We're on a mission to build a better future where technology.</p>
              <ul class="list-unstyled social">
                <li>
                  <nuxt-link to="#"><i class="fab fa-facebook"></i></nuxt-link>
                  <nuxt-link to="#"><i class="fab fa-twitter-square"></i></nuxt-link>
                  <nuxt-link to="#"><i class="fab fa-instagram"></i></nuxt-link>
                  <nuxt-link to="#"><i class="fab fa-google"></i></nuxt-link>
                </li>
              </ul>
            </div>
            <div class="col-md-3 col-sm-6 col-xs-12">
               <div class="title">
                  <h3>Address</h3>
               </div>
               <div class="contact-widget">
                  <p><span>Phone:</span>+1 605 722 2032</p>
                  <p><span>Email:</span>example@mail.com</p>
                  <p><span>Address:</span>Charlotte, North Carolina, United States</p>
               </div>
            </div>
            <div class="col-md-3 col-sm-6 col-xs-12">
               <div class="title">
                  <h3>Quick Links</h3>
               </div>
               <div class="contact-widget">
                  <nuxt-link to="#">Privacy Policy</nuxt-link>
                  <nuxt-link to="#">About Us</nuxt-link>
                  <nuxt-link to="#">Contact Us</nuxt-link>
               </div>
            </div>
            <div class="col-md-3 col-sm-6 col-xs-12">
               <div class="title">
                  <h3>Twitter</h3>
               </div>
               <div class="contact-widget">
                 <i class="fab fa-twitter-square" style="color: deepskyblue"></i>
                 Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                 Accusamus debitis dignissimos fuga fugit nemo .1
               </div>
              <div class=" mt-md-4">
                  <span class="swiper-btn-prev">
                    <i class="fas fa-angle-left"></i>
                  </span>
                        <span class="swiper-btn-next">
                    <i class="fas fa-angle-right"></i>
                  </span>
              </div>
            </div>
          </div>
      </div>
</template>

<script>
export default {
  name: "social"
}
</script>

<style scoped>
  .container{
    margin-top: 70px;
    margin-bottom: 80px;
  }
  .appilo-title{
    font-size: 16px;
    line-height: 24px;
    color: black;
    font-weight: 700;
    margin-top: 25px;
    margin-bottom: 15px;
  }
  .social a {
    color:#8b8b8b;
    font-size:21px;
    -webkit-transition:all .4s ease;
    transition:all .4s ease
  }
  .social a+a {
    margin-left:20px
  }
  .social a:hover {
    background:-webkit-gradient(linear,left top,right top,from(#6541c1),color-stop(98%,#d43396),to(#d43396));
    background:linear-gradient(to right,#6541c1 0,#d43396 98%,#d43396 100%);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent
  }
  .title{
    margin-bottom: 34px;
  }
  h3{
    margin: 0;
    color: #1a0a37;
    font-size: 18px;
    font-weight: 600;
    line-height: 24px;
  }
  .contact-widget span{
    color: #170b35;
    font-weight: 700;
    padding-right: 10px;
  }
  .contact-widget p{
    font-size: 17px;
    line-height: 24px;
    margin: 0;
    font-weight: 600;
    color: #656565;
  }
  .contact-widget a{
    text-decoration: none;
    padding-right: 10px;
    font-size: 17px;
    line-height: 24px;
    margin: 0;
    font-weight: 600;
    color: #656565;
  }
  .contact-widget a:hover{
    font-size: 17px;
    line-height: 24px;
    margin: 0;
    font-weight: 600;
    color:#d23397;
  }
  .swiper-btn-prev{
    width: 26px;
    height: 26px;
    border-radius: 50%;
    color: #fff;
    font-size: 16px;
    line-height: 26px;
    margin-right: 10px;
    padding: 0;
    text-align: center;
    background: #6b40bf;
    -webkit-transition: all .4s ease;
    transition: all .4s ease;
    display: inline-block;
    vertical-align: middle;
    cursor: pointer;
  }
  .swiper-btn-next{
    width: 26px;
    height: 26px;
    border-radius: 50%;
    color: #fff;
    font-size: 16px;
    line-height: 26px;
    margin: 0;
    padding: 0;
    text-align: center;
    background: #6b40bf;
    -webkit-transition: all .4s ease;
    transition: all .4s ease;
    display: inline-block;
    vertical-align: middle;
    cursor: pointer;
  }
</style>
