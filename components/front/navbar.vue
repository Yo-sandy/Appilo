<template>
       <div class="bg-overlay">
         <div class="container" >
           <div class="row">
             <div class="my-menu">
               <nav class="navbar navbar-expand-xl navbar-light bg-transparent">
                 <nuxt-link to="#" class="me-auto">
                   <img src="/logo-appilo.png" alt="">
                 </nuxt-link>
                 <button class="navbar-toggler" type="button"
                         data-toggle="collapse" data-target="#navbarSupportedContent"
                         aria-controls="navbarSupportedContent" aria-expanded="false"
                         aria-label="Toggle navigation">
                   <span class="navbar-toggler-icon"></span>
                 </button>
                 <div class="collapse navbar-collapse" id="navbarSupportedContent">
                   <ul class="navbar-nav ms-auto">
                     <li class="nav-item"><nuxt-link to="#" >Home</nuxt-link></li>
                     <li class="nav-item"><nuxt-link to="#"  >Features</nuxt-link></li>
                     <li class="nav-item"><nuxt-link to="#" >How it Works</nuxt-link></li>
                     <li class="nav-item"><nuxt-link to="#" >How it Works</nuxt-link></li>
                     <li class="nav-item"><nuxt-link to="#">Pricing</nuxt-link></li>
                     <li class="nav-item"><nuxt-link to="#" class="btn">Download</nuxt-link></li>
                   </ul>
                 </div>
               </nav>
             </div>
           </div>
           <front-home/>
         </div>
       </div>
</template>

<script>
export default {
name: "navbar"
}
</script>

<style scoped>
  .bg-overlay{
    background-image:  url("/slider-bg-1(1).jpg");
    background-size: cover;
    background-position-x: center;
    background-position-y: top;
    background-repeat: no-repeat;
    background-attachment: scroll;
    background-origin: padding-box;
    background-clip: border-box;
    z-index: 1;
  }
  .navbar{
    top: 30px;
  }
  .my-menu{
    margin: 0 auto;
  }
a{
  text-decoration: none;
  padding-left: 20px;
  padding-right: 9px;
  color: white;
  font-weight: bold;
}
a:hover{
  color: black;
}
li{
  display: inline-block;
}



/*btn*/
  .btn{
    border: 0;
    outline: 0;
    background: #fff;
    color: #190a32;
    font-weight: 600;
    font-size: 15px;
    border-radius: 18px;
    display: inline-block;
    padding: 4.5px 21.5px;
    -webkit-transition: all .4s ease;
    transition: all .4s ease;
  }
  .btn:hover{
    color: white;
    background: linear-gradient(to right, #6541c1 0%, #d43396 98%, #d43396 100%);
  }

</style>
