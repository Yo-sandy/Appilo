<template>
<div class="d-flex text-center">
    <div class="col-md-4 hvr-underline-from-center">
      <div class="item">
        <div class="text-center">
          <i class="fas fa-shield-alt "></i>
          <h3>Easy to Edit</h3>
          <p>
            We use a customized application
            <br>
            specifically designed a testing gnose
            <br>
            to keep away for people.
          </p>
          <div class="line"></div>
        </div>
      </div>
    </div>
    <div class="col-md-4 hvr-underline-from-center">
      <div class="item">
        <div class="text-center">
          <i class="fas fa-cloud-download-alt"></i>
          <h3>Design & Branding</h3>
          <p>
            We use a customized application
            <br>
            specifically designed a testing gnose
            <br>
            to keep away for people.
          </p>
          <div class="line"></div>
        </div>
      </div>
    </div>
    <div class="col-md-4 hvr-underline-from-center">
      <div class="item">
        <div class="text-center">
          <i class="fas fa-palette"></i>
          <h3>Easy to Edit</h3>
          <p>
            We use a customized application
            <br>
            specifically designed a testing gnose
            <br>
            to keep away for people.
          </p>
          <div class="line"></div>
        </div>
      </div>
    </div>
</div>
</template>

<script>
export default {
  name: "carousel"
}
</script>

<style scoped>
i{
  font-size: 45px;
}
.item:hover i{
  background: -webkit-linear-gradient(#6541c1 0,#d43396 98%,#d43396 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
h3{
  font-size: 20px;
  font-weight: 500;
  color: #150a33;
  margin-top: 17px;
  margin-bottom: 17px;
}
p{
  margin-bottom: 50px;
}

/* hover*/
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
