<template>
   <div> 
    <app-navbar/>
    <Hero/>
    <Works/>
    <Campaigns/>
  </div>
</template>

<script>
//  Import Components  //
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import Works from './components/Works.vue'
import Campaigns from './components/Campaigns.vue'

export default {
//  Register Components  //
  components: {
    'app-navbar': Navbar,
     Hero,
     Works,
     Campaigns
  },

  data () {
    return {
  
    }
  }
}
</script>

<style>
  html {
    font-size: 10px;
    margin: 0;  
    padding: 0;
    border: 0;
  }

  body {
    font-family: 'Quicksand', sans-serif;
  }
</style>