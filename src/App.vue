<template>
   <div> 
    <app-navbar></app-navbar>
    <app-hero></app-hero>
    <app-works></app-works>
    <app-campaigns></app-campaigns>
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
    'app-hero': Hero,
    'app-works': Works,
    'app-campaigns': Campaigns
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

  .container-fluid {
   padding-top: 5rem;
   background: #FDFDFD;
   };
</style>