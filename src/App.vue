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
    margin: 0;  
    padding: 0;
    border: 0;
  }

  body {
    font-family: 'Quicksand', sans-serif;
  }

  .sectionHeading {
    color: #FF7575;
    font-weight: bold;
    font-size: 3.5rem;
  }
</style>