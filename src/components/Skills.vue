<template>
 <section>
    <v-container grid-list-lg id="skills">
        <v-layout row>
            <v-flex xs12 md12 class="text-xs-center display-1 font-weight-black my-5" data-aos="zoom-in">Technology Skills</v-flex>
        </v-layout>

        <v-layout row wrap>
          
            <v-flex xs12 md4 pa-4>
                <v-card class="card card-shadow" height="300px" data-aos="zoom-in">
                  <div xs12 md4 class=" img-size-max mb">
                    
                       <img src="../assets/logo.png" alt="" class="img">
                 
                  </div>
                    <div class="body-2 text-md-center text-xs-center mb">
                     <p>VUE.JS</p>
                    </div>
                    <v-container class="mt-2 text-md-center text-xs-center">   
                      <v-progress-linear
                      
                      v-model="vue"
                      class="position progress"
                      color="grey darken-3"
                      height="10"
                      >
                        </v-progress-linear>
                     </v-container>
                </v-card>
            </v-flex>

             <v-flex xs12 sm12 md4 pa-4>
                <v-card class="card card-shadow" height="300px" data-aos="zoom-in">
                  <div class=" img-size-max mb">
                 
                       <img src="../assets/javascript.png" alt="javascript" class="img">
               
                  </div>
                    <div class="body-2 text-md-center text-xs-center">
                     <p>JAVASCRIPT</p>
                    </div>
                    <v-container class="mt-2 text-md-center text-xs-center">
                        <v-progress-linear
                      class="position progress"
                      color="grey darken-3"
                      height="10"
                      value="60">
                        </v-progress-linear>
                    </v-container>
                </v-card>
            </v-flex>

            <v-flex xs12 md4 pa-4>
                <v-card class="card card-shadow" height="300px" data-aos="zoom-in">
                  <div xs12 md4 class=" img-size-max mb">
                    
                       <img src="../assets/tys.png" alt="" class="img">
                 
                  </div>
                    <div class="body-2 text-md-center text-xs-center mb">
                     <p>TYPESCRIPT(learning in progress)</p>
                    </div>
                    <v-container class="mt-2 text-md-center text-xs-center">
                        <v-progress-linear
                      class="position progress"
                      color="grey darken-3"
                      height="10"
                      value="25">
                        </v-progress-linear>
                    </v-container>
                </v-card>
            </v-flex>

             <v-flex xs12 sm12 md4 pa-4>
                <v-card class="card card-shadow" height="300px" data-aos="zoom-in">
                  <div class=" img-size-max mb">
                 
                       <img src="../assets/html.png" alt="javascript" class="img">
               
                  </div>
                    <div class="body-2 text-md-center text-xs-center">
                     <p>HTML5</p>
                    </div>
                    <v-container class="mt-2 text-md-center text-xs-center">
                        <v-progress-linear
                      class="position progress"
                      color="grey darken-3"
                      height="10"
                      value="80">
                      
                        </v-progress-linear>
                    </v-container>
                </v-card>
            </v-flex>

             <v-flex xs12  md4 pa-4>
                <v-card class="card card-shadow" height="300px" data-aos="zoom-in">
                  <div class=" img-size-max mb ml">
                
                       <img src="../assets/css33.png" alt="nodejs" class="img">
                 
                  </div>
                    <div class="body-2 text-md-center text-xs-center">
                     <p>CSS3</p>
                    </div>
                    <v-container class="mt-2 text-md-center text-xs-center">
                        <v-progress-linear
                      class="position progress"
                      color="grey darken-3"
                      height="10"
                      value="70">
                        </v-progress-linear>
                    </v-container>
                </v-card>
            </v-flex>

            <v-flex xs12 md4 pa-4>
                <v-card class="card card-shadow" height="300px" data-aos="zoom-in">
                  <div xs12 md4 class=" img-size-max mb">
                    
                       <img src="../assets/bootstrap.png" alt="" class="img">
                 
                  </div>
                    <div class="body-2 text-md-center text-xs-center mb">
                     <p>BOOTSTRAP4</p>
                    </div>
                    <v-container class="mt-2 text-md-center text-xs-center">
                        <v-progress-linear
                      class="position progress"
                      color="grey darken-3"
                      height="10"
                      value="70">
                        </v-progress-linear>
                    </v-container>
                </v-card>
            </v-flex>

             <v-flex xs12 sm12 md4 pa-4>
                <v-card class="card card-shadow" height="300px" data-aos="zoom-in">
                  <div class=" img-size-max mb">
                 
                       <img src="../assets/git2.png" alt="javascript" class="img">
               
                  </div>
                    <div class="body-2 text-md-center text-xs-center">
                     <p>GITHUB</p>
                    </div>
                    <v-container class="mt-2 text-md-center text-xs-center">
                        <v-progress-linear
                      class="position progress"
                      color="grey darken-3"
                      height="10"
                      value="60">
                      
                        </v-progress-linear>
                    </v-container>
                </v-card>
            </v-flex>

             <v-flex xs12  md4 pa-4>
                <v-card class="card card-shadow" height="300px" data-aos="zoom-in">
                  <div class=" img-size-max mb ml">
                
                       <img src="../assets/firebase.png" alt="nodejs" class="img">
                 
                  </div>
                    <div class="body-2 text-md-center text-xs-center">
                     <p>FIREBASE</p>
                    </div>
                    <v-container class="mt-2 text-md-center text-xs-center">
                        <v-progress-linear
                      class="position progress"
                      color="grey darken-3"
                      height="10"
                      value="45">
                        </v-progress-linear>
                    </v-container>
                </v-card>
            </v-flex>


            <v-flex xs12 md4 pa-4>
                <v-card class="card card-shadow" height="300px" data-aos="zoom-in">
                  <div xs12 md4 class=" img-size-max mb">
                    
                       <img src="../assets/Runtime-logo-Node2.jpg" alt="" class="img">
                 
                  </div>
                    <div class="body-2 text-md-center text-xs-center mb">
                     <p>NODEJS</p>
                    </div>
                    <v-container class="mt-2 text-md-center text-xs-center">
                        <v-progress-linear
                      class="position progress"
                      color="grey darken-3"
                      height="10"
                      value="45">
                        </v-progress-linear>
                    </v-container>
                </v-card>
            </v-flex>

            <v-flex xs12  md4 pa-4>
                <v-card class="card card-shadow" height="300px" data-aos="zoom-in">
                  <div class=" img-size-max mb">
                
                       <img src="../assets/laravel.png" alt="nodejs" class="img">
                 
                  </div>
                    <div class="body-2 text-md-center text-xs-center">
                     <p>LARAVEL (learning in progress)</p>
                    </div>
                    <v-container class="mt-2 text-md-center text-xs-center">
                        <v-progress-linear
                      class="position progress"
                      color="grey darken-3"
                      height="10"
                      value="35">
                        </v-progress-linear>
                    </v-container>
                </v-card>
            </v-flex>

             <v-flex xs12 sm12 md4 pa-4>
                <v-card class="card card-shadow" height="300px" data-aos="zoom-in">
                  <div class=" img-size-max mb">
                 
                       <img src="../assets/pscc2.png" alt="javascript" class="img">
               
                  </div>
                    <div class="body-2 text-md-center text-xs-center">
                     <p>PHOTOSHOP</p>
                    </div>
                    <v-container class="mt-2 text-md-center text-xs-center">
                        <v-progress-linear
                      class="position progress"
                      color="grey darken-3"
                      height="10"
                      value="70">
                      
                        </v-progress-linear>
                    </v-container>
                </v-card>
            </v-flex>

             <v-flex xs12  md4 pa-4>
                <v-card class="card card-shadow" height="300px" data-aos="zoom-in">
                  <div class=" img-size-max mb ml">
                
                       <img src="../assets/ai2.png" alt="nodejs" class="img">
                 
                  </div>
                    <div class="body-2 text-md-center text-xs-center">
                     <p>ILLUSTRATOR</p>
                    </div>
                    <v-container class="mt-2 text-md-center text-xs-center">
                        <v-progress-linear
                      class="position progress"
                      color="grey darken-3"
                      height="10"
                      value="80">
                        </v-progress-linear>
                    </v-container>
                </v-card>
            </v-flex>

            


        </v-layout>
    </v-container>
  </section>
</template>

<style>

.img-size-max{
  max-width: 200px;
  max-height: 200px;
  margin: 10px auto;
}
.img {
    border-style: none;
    margin-top: 15px;
}
.position {
    margin: 0rem 0;
}
.progress{
      border-radius: 1.25rem;
}
.move{
  animation: 2s;
}
.vue{
  width: 65%;
  animation:2s;
}
@keyframes progressAnimationStrike {
     from { width: 0 }
     to   { width: 100% }
}
.mb {
  margin-bottom: 15px;
}
.mb2 {
  margin-bottom: 35px;
}
.ml2 {
    margin-left: 22px !important;
}
.card-shadow{
    -webkit-box-shadow: 0px 5px 25px 0px rgba(0, 0, 0, 0.2);
          box-shadow: 0px 5px 25px 0px rgba(0, 0, 0, 0.2);
}
</style>

<script>
  export default {
    data () {
      return {
        vue: 50,
        js: 50,
        react:25,
      }
    }
  }
</script>