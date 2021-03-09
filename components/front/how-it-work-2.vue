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
      <div class="col-md-6">
        <img src="/data-moc-1-13-1-1-3-1.png" alt="">
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
  background: linear-gradient(to right,#6541c1 0,#d43396 98%,#d43396 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
img{
  border: none;
  border-radius: 0;
  box-shadow: 0 16px 43px rgba(78,48,135,.24);
  vertical-align: middle;
}
/* tool-6 close*/
</style>
