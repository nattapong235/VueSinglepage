<template>
  <v-app>
    <Navbar/>
      <v-content transition="slide-x-transition">
      <router-view ></router-view>
      <Homepage/>
      <Homedetail/>
      <Homeexperience/>
      <Skills/>
      <Portfolio/>
      <Footer/>
    </v-content>
  </v-app>
</template>

<script>
import Navbar from './components/Navbar'
import Homepage from './components/Homepage'
import Homedetail from './components/Homedetail'
import Homeexperience from './components/Homeexperience'
import Skills from './components/Skills'
import Portfolio from './components/Portfolio'
import Footer from './components/Footer'
export default {
  name: 'App',
  components: {
    Navbar,
    Homepage,
    Homedetail,
    Homeexperience,
    Skills,
    Portfolio,
    Footer
  },
  // views: {
  //   Education,Skill,About
  // },
  data () {
    return {
    }
  }
}
</script>

<style scoped>
</style>
