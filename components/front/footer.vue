<template>
  <footer class="appilo-footer">
    <div class="subscribe-section">
      <div class="container">
        <div class="row">
          <div class="appilo-sec-title text-center">
            <h2>Subscribe to Our Newsletter</h2>
            <p>
              A Private Limited is the most popular type of partnership Malta. The limited liability
              <br>
              is, in fact, the only type of company allowed by Companies.
            </p>
          </div>
              <div class="wpcf7">
                <form style="justify-content: space-between;display: flex">
                  <div class="left-content ">
                    <i class="fas fa-envelope"></i>
                    <input class="your-email" type="email" size="40" placeholder="example@gmail.com"/>
                  </div>
                  <div class="right-content">
                    <input type="submit" class="submit" value="Subscribe Now">
                  </div>
                </form>
              </div>
            </div>
         </div>
        <front-social/>
        <div class="footer-bottom">
            <div class="container">
                <div class="footer-copyright" style="justify-content: space-between;display: flex">
                      <div class="left-item">
                          <p>
                            © 2018, appilo Theme by Themexriver Team |
                              <nuxt-link to="#">Privacy Policy</nuxt-link> |
                              <nuxt-link to="#">Site Map</nuxt-link>
                          </p>
                      </div>
                  <div class="right-item">
                      <p>All Right Reserved</p>
                  </div>
                </div>
            </div>
        </div>
    </div>
  </footer>
</template>

<script>
export default {
name: "footer"
}
</script>

<style scoped>


.appilo-footer{
  background: transparent url("/footer-bg-1-1-26-1-1-2-1-1-2-1-1.png");
  background-size: cover;
}
.appilo-footer .subscribe-section{
  padding-top: 120px;
}
.subscribe-section{
  padding-bottom: 20px;
}
.appilo-sec-title{
  margin-bottom: 70px;
  text-align: center;
}
h2{
  font-size: 32px;
  font-weight: 700;
  line-height: 48px;
  color: #170b35;
}
p{
  font-size: 19px;
  line-height: 26px;
  color: #656565;
  margin-top: 20px;
}
.text-center{
  text-align: center!important;
}
.wpcf7{
  background: linear-gradient(to right, #6541c1 0%, #d43396 98%, #d43396 100%);
  border-radius: 100px;
  padding: 35px 35px;
  box-shadow: 0 23px 42px rgba(0,0,0,.2);
}

.left-content{
  position: relative;
  top: 10px;
}
.left-content i{
  font-size: 24px;
  color: #eae9ec;
  display: inline-block;
}
input{
  overflow: visible;
  color: #eae9ec;
  line-height: inherit;
}
.appilo-footer .subscribe-section ::-moz-placeholder {
  color:#fff;
  opacity:1
}
.your-email{
  background-color: transparent;
  border: 0;
  outline: 0;
  font-size: 16px;
  font-weight: 700;
  border-bottom: 1px solid #eae9ec;
  max-width: 220px;
  margin-left: 20px;
}
.submit {
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
.submit:hover {
  background:#000;
  color:#fff
}
/*=====================================================Footer Bottom========================================*/
.footer-bottom .footer-copyright {
  width: 100%;
  display: table;
  border-top:1px solid #b7b7b7;
  padding: 15px 0;
}
.footer-copyright p{
  margin: 0;
  font-size: 16px;
  line-height: 26px;
  color: #383838;
  letter-spacing: .025em;
}
.left-item p a{
  color: #656565;
  display: inline-block;
  border-bottom: 1px solid #656565;
  line-height: 1em;
  vertical-align: middle;
}
</style>
