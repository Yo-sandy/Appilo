<template>
<div class="container" style="padding: 112px 0 82px">
  <div class="row">
      <div class="text-center">
          <h2>Get in Reasonable Price</h2>
        <p>
          A Private Limited is the most popular type of partnership Malta. The limited liability
          <br>
          is, in fact, the only type of company allowed by Companies.
        </p>
        <ul class="list-unstyled">
            <li><nuxt-link to="#" class="monthly text-decoration-none">Monthly</nuxt-link></li>
            <li><i class="fas fa-toggle-on tool-icon"></i></li>
            <li><nuxt-link to="#" class="yearly text-decoration-none">Yearly</nuxt-link></li>
        </ul>
      </div>
      <front-honorable-client/>
  </div>
</div>
</template>

<script>
export default {
name: "pricing"
}
</script>

<style scoped>
ul{
  margin-top: 100px;
  display: flex;
  justify-content: center;
}
.tool-icon{
  font-size: 45px;
  background: linear-gradient(to right,#6541c1 0,#d43396 98%,#d43396 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  line-height: 1;
  margin-left: 15px;
  margin-right: 15px;
  cursor: pointer!important;
}
.monthly{
  font-size:20px;
  font-weight: bold;
  color: #c3c3c3;
}
.yearly{
  font-size:20px;
  font-weight: bold;
  color: black;
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
</style>
