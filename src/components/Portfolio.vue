<template>
  <section id="portfolio">
    <v-container>
       <v-layout row>
            <v-flex xs12 md12 class="text-xs-center display-1 font-weight-black my-5" data-aos="zoom-in">Portfolio</v-flex>
        </v-layout>

         <v-layout row wrap> 
          <v-flex xs12 md12>  
            <v-tabs centered icons-and-text data-aos="fade-up">
                <v-tabs-slider color="grey"></v-tabs-slider>
                    <v-tab role="tablist" data-toggle="tab" aria-hidden="true" href="#web-development">
                        Website
                        <v-icon large color="black">web</v-icon>
                      </v-tab>

                      <v-tab role="tablist" data-toggle="tab" aria-hidden="true" href="#graphic-design">
                        Design
                        <v-icon large color="black">photo_library</v-icon>
                      </v-tab>

                      <v-tab role="tablist" data-toggle="tab" aria-hidden="true" href="#Photography">
                        Photography
                        <v-icon large color="black">camera_alt</v-icon>
                      </v-tab>
              </v-tabs>
            </v-flex>
        </v-layout>

      <div class="gallery mt-5">
        
        <div class="tab-pane active" id="web-development">  
        <div class="ml-2 mr-2">
         <v-layout row wrap> 

              <v-flex xs12 md6 pa-3>      
                   <div class="cc-porfolio-image img-raised" data-aos="fade-up" data-aos-anchor-placement="top-bottom">
                    <a href="#web-development">
                      <figure class="cc-effect"><img src="../assets/web2.jpg" alt="Image"/>
                        <figcaption>
                          <div class="h4">Website Design</div>
                          <p>Web Development</p>
                        </figcaption>
                      </figure>
                    </a>
                  </div>
              </v-flex>  
             
              <v-flex xs12 md6 pa-3>          
                  <div class="cc-porfolio-image img-raised" data-aos="fade-up" data-aos-anchor-placement="top-bottom">
                    <a href="#web-development">
                      <figure class="cc-effect"><img src="../assets/reseme.jpg" alt="Image"/>
                        <figcaption>
                          <div class="h4">Website Portfolio</div>
                          <p>Web Development</p>
                        </figcaption>
                      </figure>
                    </a>
                  </div> 
              </v-flex>  

          </v-layout>      
        </div>
        </div>      
     </div>         
                                
       
    </v-container>
  </section>
</template>

<style>
.theme--light.v-tabs__bar {
    background-color: #fafafa;
}
.gallery .cc-porfolio-image figure {
  position: relative;
  overflow: hidden;
  text-align: center;
}

.gallery .cc-porfolio-image figure img {
  position: relative;
  display: block;
  max-width: 100%;
  opacity: 1;
}

.gallery .cc-porfolio-image figure figcaption {
  position: absolute;
  color: #fff;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.gallery .cc-porfolio-image figure figcaption,
.gallery .cc-porfolio-image figure figcaption > a {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.gallery .cc-porfolio-image figure figcaption > a {
  z-index: 1000;
  text-indent: 200%;
  white-space: nowrap;
  font-size: 0;
  opacity: 0;
}

.gallery .cc-porfolio-image figure .h4,
.gallery .cc-porfolio-image figure p {
  margin: 0;
}

.gallery figure.cc-effect figcaption::before,
.gallery figure.cc-effect figcaption::after {
  position: absolute;
  content: '';
  opacity: 0;
}

.gallery figure.cc-effect figcaption::before {
  top: 10px;
  right: 10px;
  bottom: 10px;
  left: 10px;
  -webkit-transform: scale(0, 0);
  transform: scale(0, 0);
  -webkit-transform-origin: 0 0;
  transform-origin: 0 0;
}

.gallery figure.cc-effect figcaption::after {
  top: 10px;
  right: 10px;
  bottom: 10px;
  left: 10px;
  -webkit-transform: scale(0, 0);
  transform: scale(0, 0);
  -webkit-transform-origin: 100% 0;
  transform-origin: 100% 0;
}

.gallery figure.cc-effect .h4 {
  margin-top: 25%;
  -webkit-transition: -webkit-transform 0.35s;
  transition: -webkit-transform 0.35s;
  transition: transform 0.35s;
  transition: transform 0.35s, -webkit-transform 0.35s;
  opacity: 0;
}

@media (max-width: 480px) {
  .gallery figure.cc-effect .h4 {
    font-size: 14px;
  }
}

.gallery figcaption .container {
  position: absolute;
  width: 100%;
  bottom: 20px;
}

.gallery figure.cc-effect p,
.gallery figure.cc-effect button {
  padding: 0.5em 2em;
  text-transform: uppercase;
  letter-spacing: 1px;
  -webkit-transition: -webkit-transform 0.35s;
  transition: -webkit-transform 0.35s;
  transition: transform 0.35s;
  transition: transform 0.35s, -webkit-transform 0.35s;
  opacity: 0;
}

.gallery figure.cc-effect img,
.gallery figure.cc-effect .h4 {
  -webkit-transform: scale(1.06, 1.06);
  transform: scale(1.06, 1.06);
}

.gallery figure.cc-effect img,
.gallery figure.cc-effect figcaption::before,
.gallery figure.cc-effect figcaption::after,
.gallery figure.cc-effect p {
  -webkit-transition: opacity 0.35s, -webkit-transform 0.35s;
  transition: opacity 0.35s, -webkit-transform 0.35s;
  transition: opacity 0.35s, transform 0.35s;
  transition: opacity 0.35s, transform 0.35s, -webkit-transform 0.35s;
}

.gallery figure.cc-effect:hover img {
  opacity: 1;
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}

.gallery figure.cc-effect:hover figcaption::before,
.gallery figure.cc-effect:hover figcaption::after {
  opacity: 1;
  -webkit-transform: scale(1);
  transform: scale(1);
}

.gallery figure.cc-effect:hover figcaption:before {
  background: rgba(27, 23, 23, 0.5);
}

.gallery figure.cc-effect:hover .h4,
.gallery figure.cc-effect:hover p,
.gallery figure.cc-effect:hover button {
  opacity: 1;
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
  color: #fff;
}

.gallery figure.cc-effect:hover figcaption::after,
.gallery figure.cc-effect:hover .h4,
.gallery figure.cc-effect:hover p,
.gallery figure.cc-effect:hover img {
  -webkit-transition-delay: 0.15s;
  transition-delay: 0.15s;
}
.img-raised {
    -webkit-box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3);
    box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3);
}
.tab-content>.active {
    display: block;
}
.tab-content>.tab-pane {
    display: none;
}
</style>
