<template>
    <v-container fluid fill-height class=" bg-img" style="max-height: 100vh;" id="home">
         <v-layout justify-center align-center column pa-5>
           <div class="mt-0 cc-profile-image hidden-sm-and-down"><a href="#"><img src="../assets/2.jpg" alt="Image"/> </a></div>
            <div class="display-2 mt-4 font-weight-bold white--text text-xs-center mb-3">NATTAPONG   KAEWSANGSUK</div>

            <div class="display-1 font-weight-bold amber--text text-xs-center"><vue-typed-js :strings="['Front-End Developer','Web Developer', 'WebDesign']" :loop="true" @onComplete="doSmth()" :typeSpeed="150" :backSpeed="20" :startDelay="1000">
                    <h2><span class="typing"></span></h2>
            </vue-typed-js></div>
            <v-btn fab class="mt-5 black" href="#about">
            <v-icon large color="white">expand_more</v-icon>
            </v-btn>
        </v-layout>

    </v-container>
  


   

  
</template>

<script>
export default {
  name: 'home',
    data () {
      return {
      }
    }
  }
</script>

<style>
/* ------------ background ------------- */
.bg-img {   
    background-image: url("../assets/pic4.png");
    display: -webkit-box;
    display: -ms-flexbox;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    text-align: center;
    width: 100%;

    background-repeat: no-repeat;
    background-size: cover;
    padding-bottom: 9vh;
}
</style>

