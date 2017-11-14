<template>
   <div> 
    <app-navbar></app-navbar>
    <app-hero></app-hero>
    <app-campaign></app-campaign>
  </div>
</template>

<script>
//  Import Components  //
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import Campaign from './components/Campaign.vue'

export default {
//  Register Components  //
  components: {
    'app-navbar': Navbar,
    'app-hero': Hero,
    'app-campaign': Campaign
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
  }
  body {
    font-family: 'Quicksand', sans-serif;
  }
</style>