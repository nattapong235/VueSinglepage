<template>
    <v-container text-xs-center id="about" mt-4>  
        <div class="mb-4  display-1 font-weight-bold black--text text-xs-center" data-aos= "zoom-in">About Me</div>    
        <v-layout row>
            <v-flex>
                <v-card dark color="grey lighten-5" class="card-body" data-aos="fade-up" data-aos-offset="10">
                <v-card-text>
                <v-layout row pa-3 wrap>
                    <v-flex xs12 md6>
                        <div class="font-weight-bold display-1 black--text mt-0">Who I am.</div>
                        <div class="subheading mt-4 ml-3 black--text">
                        <p class="text-sm-left mb-4">Hello! I am Fron-end Web Developer, Graphic Designer 
                           and Photographer. 
                           Thank you for your interest in my history.</p></div>
                        <div class="font-weight-bold display-1 black--text">Personality.</div>
                            <div class="title black--text ma-2 mt-3  pa-2 ">
                                <div class="pa-1 text-sm-left"><li><strong> learner </strong></li> </div>
                                <div class="pa-1 text-sm-left"><li><strong>Responsible</strong></li></div>
                                <div class="pa-1 text-sm-left"><li><strong>Friendly</strong></li></div>
                            </div>
                    </v-flex>

                    <v-flex xs12 md6 order-lg2 >
                        <div class="font-weight-bold display-1 black--text mt-0">Basic Information.</div>
                        <v-layout row class="subheading text-md-center black--text mt-4">
                                <div><strong class="text-uppercase mb-4  pl-5">Birth:</strong></div>
                                <div class="ml-5 pl-5 text-sm-center">12 September 1992</div>
                        </v-layout>
                        <v-layout row class="subheading text-md-center text-sm-left black--text  mt-4">
                                <div><strong class="text-uppercase text-sm-left mb-4  pl-5">Religion:</strong></div>
                                <div class="ml-5 pl-5 text-sm-center">Buddhist</div>
                        </v-layout>
                        <v-layout row class="subheading text-md-center black--text  mt-4">
                                <div><strong class="text-uppercase mb-4 pl-5">Email:</strong></div>
                                <div class="ml-5 pl-4 text-sm-left">nattapong235.k@gmail.com</div>
                        </v-layout>
                        <v-layout row class="subheading text-md-center black--text  mt-4">
                                <div><strong class="text-uppercase mb-4  pl-5">Phone:</strong></div>
                                <div class="ml-5 pl-5 text-sm-center">082 - 823 - 5237</div>
                        </v-layout>
                        <v-layout row class="subheading text-md-center black--text mt-4">
                                <div><strong class="text-uppercase mb-4  pl-5">Address:</strong></div>
                                <div class="ml-5 pl-2 text-sm-left">801 /51 Happy Condo Ladprao 101 , Wang Thonglang , Bangkok 10310</div>
                        </v-layout>
                    </v-flex>
                </v-layout>               
                </v-card-text>
        </v-card>
                   <div class="button-container mb-5" style="height:45px">
                        <v-container xm12 xs12 md6 >
                            <v-btn fab medium  href="https://www.facebook.com/znorth.nattapong" target="_blank">
                                    <v-icon large class="f-hover">mdi-facebook</v-icon>
                            </v-btn>

                            <v-btn  fab medium box  href="https://github.com/nattapong235" target="_blank">
                                    <v-icon large class="git-hover">mdi-github-circle</v-icon>
                            </v-btn>

                            <v-btn fab medium box  href="https://www.instagram.com/northto235" target="_blank">
                                   <v-icon large>mdi-instagram</v-icon>       
                            </v-btn>       

                        </v-container>
                    </div>
            </v-flex>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'about'
};
</script>

<style>
.card-body {
  min-height:425px;
  border: 0;
  border-radius: 0.1875rem;
  display: inline-block;
  position: relative;
  overflow: hidden;
  width: 100%;
  margin-bottom: 20px;
  -webkit-box-shadow: 0px 5px 25px 0px rgba(0, 0, 0, 0.2);
          box-shadow: 0px 5px 25px 0px rgba(0, 0, 0, 0.2);
}
.button-container {
  text-align: center;
  margin-top: -88px;
}
.theme--dark.v-footer {
    background: rgb(250, 250, 250);
    color: #fff;
}
.f-hover {
  color: rgb(0, 153, 255);
}
.ig-hover {
  color: rgb(112, 13, 91);
}
.git-hover {
  color: rgb(255, 94, 0);
}

</style>