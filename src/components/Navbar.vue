<template>
<span>
        <v-toolbar app dark fixed-top color="black">
          <v-toolbar-side-icon class="hidden-md-and-up" @click="drawer = !drawer"></v-toolbar-side-icon>
          <v-spacer></v-spacer>
          <v-toolbar-items fixed-top class="hidden-sm-and-down fixed-top">   
            <v-btn flat scroll-target href="#home" >HOME</v-btn>
            <v-btn flat scroll-target href="#about" >ABOUT</v-btn>
            <v-btn flat scroll-target href="#experience">EXPERIENCE</v-btn>
            <v-btn flat scroll-target href="#skills" >SKILLS</v-btn>
            <v-btn flat scroll-target href="#portfolio">PORTFOLIO</v-btn>
          </v-toolbar-items>
          <v-spacer></v-spacer>
        </v-toolbar>
        <v-navigation-drawer 
        v-model="drawer" 
          app  
          class="black text-xs-center" dark disable-resize-watcher>
              <div class="layout align-center column fill-height justify-center">
              <div class="mt-0 cc-profile-image"><a href="#"><img src="../assets/2.jpg" alt="Image"/> </a></div>
              <div class="mt-4">
                
                <v-list flat dark >
                  <template v-for="(item, index) in items">
                    <v-list-tile
                      :key="index">
                      <v-btn flat>
                  
                      <v-list-tile-action>
                          <v-icon>{{ item.icon }}</v-icon>
                      </v-list-tile-action>
                      <v-list-tile-content>
                          <v-list-tile-title>{{ item.title }}</v-list-tile-title>
                      </v-list-tile-content>
                      </v-btn>
                    </v-list-tile>
                    <v-divider :key="`divider-${index}`"></v-divider>
                    </template>
                  </v-list>
          <v-container mt-4>
                  <v-btn fab small  href="https://www.facebook.com/znorth.nattapong" target="_blank">
                          <v-icon medium class="f-hover">mdi-facebook</v-icon>
                  </v-btn>

                  <v-btn  fab small box  href="https://github.com/nattapong235" target="_blank">
                          <v-icon medium class="git-hover">mdi-github-circle</v-icon>
                  </v-btn>

                  <v-btn fab small box  href="https://www.instagram.com/northto235" target="_blank">
                          <v-icon medium>mdi-instagram</v-icon>       
                  </v-btn>  
            </v-container>     
            </div> 
          </div>
          </v-navigation-drawer>
</span> 
</template>

<script>
export default {
  name: 'Navbar',
  data (){
     return{
        drawer:false,
        items: [
          { title: 'Home', icon: 'home'},
          { title: 'About', icon: 'person'},
          { title: 'Experience', icon: 'card_travel'},
          { title: 'Skills', icon: 'apps'},
          { title: 'Portfolio', icon: 'folder' }
        ],
        right: null
      }
    }
  }
</script>

<style>
/* Profile Image Style */
@-webkit-keyframes pulsate {
  0% {
    -webkit-transform: scale(0.6, 0.6);
            transform: scale(0.6, 0.6);
    opacity: 0.0;
  }
  50% {
    opacity: 1.0;
  }
  100% {
    -webkit-transform: scale(1, 1);
            transform: scale(1, 1);
    opacity: 0.0;
  }
}
@keyframes pulsate {
  0% {
    -webkit-transform: scale(0.6, 0.6);
            transform: scale(0.6, 0.6);
    opacity: 0.0;
  }
  50% {
    opacity: 1.0;
  }
  100% {
    -webkit-transform: scale(1, 1);
            transform: scale(1, 1);
    opacity: 0.0;
  }
}

.cc-profile-image a {
  position: sticky;
}

.cc-profile-image a:before {
  content: "";
  border: 15px solid rgba(189, 189, 189, 0.87);
  border-radius: 50%;
  height: 180px;
  width: 180px;
  position: absolute;
  left: 0;
  -webkit-animation: pulsate 2s ease-out;
          animation: pulsate 2s ease-out;
  -webkit-animation-iteration-count: infinite;
          animation-iteration-count: infinite;
  opacity: 0.0;
  z-index: 99;
}

.cc-profile-image img {
  position: sticky;
  border-radius: 50%;
  height: 180px;
  width: 180px;
  padding: 0;
  margin: 0;
  border: 15px solid transparent;
  z-index: 9999;
  -webkit-transition: all .3s ease-out;
  transition: all .3s ease-out;
}

.cc-profile-image a:hover img {
  -webkit-transform: scale(1.06, 1.06);
          transform: scale(1.06, 1.06);
}

.cc-profile-image a:hover:before {
  -webkit-animation: none;
          animation: none;
}
</style>
