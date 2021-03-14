<template>
  <div style="padding:0px 0 82px;">
  <div class="container">
    <div class="row">
      <div class="text-center">
        <h2>Our Latest News</h2>
        <p>
          A Private Limited is the most popular type of partnership Malta. The limited liability
          <br>
          is, in fact, the only type of company allowed by Companies.
        </p>
      </div>
    </div>
    <div class="d-flex blog-style-one" style="padding-top: 117px;justify-content: space-between">
      <div class=" owl-item hvr-underline-from-center">
        <div class="item">
          <div class="single-blog-post">
            <div class="img-box">
              <img src="/blog-1-1-1.png"class="attachment-full size-full wp-post-image">
            </div>
            <div class="text-box">
              <ul class="meta-info d-flex">
                  <li><nuxt-link to="#">Appilo</nuxt-link></li>
                  <li><nuxt-link to="#">December 7, 2019</nuxt-link></li>
                  <li><nuxt-link to="#">admin</nuxt-link></li>
              </ul>
              <nuxt-link to="#">
                  <h3>Super App for New Devices made by touches of new tech</h3>
              </nuxt-link>
              <p>Few derived into talking being in merit long you'd his the of to had the to duties,
                it them one…</p>
              <nuxt-link to="#" class="read-more">
                Read More
                <i class="fas fa-angle-right"></i>
              </nuxt-link>
            </div>
          </div>
        </div>
      </div>
      <div class=" owl-item hvr-underline-from-center ">
        <div class="item">
          <div class="single-blog-post">
            <div class="img-box">
              <img src="/blog-1-3-1.png"class="attachment-full size-full wp-post-image">
            </div>
            <div class="text-box">
              <ul class="meta-info d-flex">
                <li><nuxt-link to="#">Appilo</nuxt-link></li>
                <li><nuxt-link to="#">December 7, 2019</nuxt-link></li>
                <li><nuxt-link to="#">admin</nuxt-link></li>
              </ul>
              <nuxt-link to="#">
                <h3>Super App for New Devices made by touches of new tech</h3>
              </nuxt-link>
              <p>Few derived into talking being in merit long you'd his the of to had the to duties,
                it them one…</p>
              <nuxt-link to="#" class="read-more">
                Read More
                <i class="fas fa-angle-right"></i>
              </nuxt-link>
            </div>
          </div>
        </div>
      </div>
      <div class=" owl-item hvr-underline-from-center">
        <div class="item">
          <div class="single-blog-post">
            <div class="img-box">
              <img src="/blog-1-1-1.png"class="attachment-full size-full wp-post-image">
            </div>
            <div class="text-box">
              <ul class="meta-info d-flex">
                <li><nuxt-link to="#">Appilo</nuxt-link></li>
                <li><nuxt-link to="#">December 7, 2019</nuxt-link></li>
                <li><nuxt-link to="#">admin</nuxt-link></li>
              </ul>
              <nuxt-link to="#">
                <h3>Super App for New Devices made by touches of new tech</h3>
              </nuxt-link>
              <p>Few derived into talking being in merit long you'd his the of to had the to duties,
                it them one…</p>
              <nuxt-link to="#" class="read-more">
                Read More
                <i class="fas fa-angle-right"></i>
              </nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>
</template>
<script>
export default {
name: "blog"
}
</script>

<style scoped>

a{
  text-decoration: none;
}

.owl-item{
  width: 353.333px;
  margin-right: 30px;
  position: relative;
  min-height: 2px;
  float: left;
  -webkit-backface-visibility: hidden;
  user-select: none;
}
h2{
  color: #170b35;
  font-size: 35px;
  font-weight: bold;
  line-height: 48px;
  margin-bottom: 20px;
}
p{
  margin-bottom: 1rem;
  font-size: 19px;
  color: grey;
}
.blog-style-one .single-blog-post:hover .img-box img {
  -webkit-transform:scale(1.05);
  transform:scale(1.05)
}
.blog-style-one .single-blog-post:hover .img-box:after {
  opacity:1
}
.blog-style-one .single-blog-post .img-box {
  border-radius:10px;
  position:relative;
  overflow:hidden;
  cursor:pointer
}
.blog-style-one .single-blog-post .img-box:after {
  content:'';
  position:absolute;
  top:0;
  left:0;
  right:0;
  bottom:0;
  border-radius:10px;
  background:rgba(0,0,0,.4);
  opacity:0;
  -webkit-transition:all .4s ease;
  transition:all .4s ease
}
.blog-style-one .single-blog-post .img-box>img {
  border-radius:10px;
  -webkit-transition:all .4s ease;
  transition:all .4s ease
}
.blog-style-one .single-blog-post .text-box h3,
.blog-style-one .single-blog-post .text-box p,
.blog-style-one .single-blog-post .text-box ul,
.blog-style-one .single-blog-post .text-box li {
  margin:0;
  padding:0;
  list-style:none
}
.blog-style-one .single-blog-post .text-box ul.meta-info {
  margin-top:40px;
  margin-bottom:15px
}
.blog-style-one .single-blog-post .text-box ul.meta-info li {
  display:inline-block;
  vertical-align:middle
}
.blog-style-one .single-blog-post .text-box ul.meta-info li:after {
  content:'';
  width:5px;
  height:5px;
  background:#6541c1;
  background:-webkit-gradient(linear,left top,right top,from(#6541c1),color-stop(98%,#d43396),to(#d43396));
  background:linear-gradient(to right,#6541c1 0,#d43396 98%,#d43396 100%);
  filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#6541c1',endColorstr='#d43396',GradientType=1);
  border-radius:50%;
  margin-left:10px;
  margin-right:7px;
  display:inline-block;
  vertical-align:middle
}
.blog-style-one .single-blog-post .text-box ul.meta-info li:last-child:after {
  display:none
}
.blog-style-one .single-blog-post .text-box ul.meta-info li a {
  display:inline-block;
  vertical-align:middle;
  color:#656565;
  font-size:16px
}
.blog-style-one .single-blog-post .text-box h3 {
  font-size:20px;
  font-weight:500;
  color:#150a33;
  line-height:30px;
  margin-bottom:15px;
  -webkit-transition:all .4s ease;
  transition:all .4s ease
}
.blog-style-one .single-blog-post .text-box h3:hover {
  background:-webkit-gradient(linear,left top,right top,from(#6541c1),color-stop(98%,#d43396),to(#d43396));
  background:linear-gradient(to right,#6541c1 0,#d43396 98%,#d43396 100%);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent
}
.blog-style-one .single-blog-post .text-box p {
  color:#656565;
  margin-bottom:15px
}
.blog-style-one .single-blog-post .text-box a.read-more {
  background:-webkit-gradient(linear,left top,right top,from(#6541c1),color-stop(98%,#d43396),to(#d43396));
  background:linear-gradient(to right,#6541c1 0,#d43396 98%,#d43396 100%);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  font-size:16px;
  font-weight:600;
  display:inline-block;
  margin-bottom:40px
}
.hvr-underline-from-center {
  display: inline-block;
  vertical-align: middle;
  -webkit-transform: perspective(1px) translateZ(0);
  transform: perspective(1px) translateZ(0);
  box-shadow: 0 0 1px rgba(0, 0, 0, 0);
  position: relative;
  overflow: hidden;
}
.hvr-underline-from-center:before {
  content: "";
  position: absolute;
  z-index: -1;
  left: 51%;
  right: 51%;
  bottom: 0;
  background: linear-gradient(to right,#6541c1 0,#d43396 98%,#d43396 100%);
  height: 4px;
  -webkit-transition-property: left, right;
  transition-property: left, right;
  -webkit-transition-duration: 0.3s;
  transition-duration: 0.3s;
  -webkit-transition-timing-function: ease-out;
  transition-timing-function: ease-out;
}
.hvr-underline-from-center:hover:before, .hvr-underline-from-center:focus:before, .hvr-underline-from-center:active:before {
  left: 0;
  right: 0;
}
</style>
