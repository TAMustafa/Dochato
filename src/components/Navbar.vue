<template>
<div class="container fixed-top">
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#">
      <img src="../assets/DCT.svg" width="82" height="71" alt="Dochato Logo">
    </a>

    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Sign up</a>
        </li>
        <li class="nav-item">
          <a class="nav-link loginbtn" href="#">Login</a>
        </li>
      </ul>
    </div>
  </nav>
</div>
</template>

<script>
export default {
  data () {
    return {
      
    }
  }
}
</script>

<style scoped>
 a {
   font-size: 2rem;
 }

 .bg-dark {
   opacity: .8;
   border-radius: 2rem;
 }

 .nav-link {
   border: white solid .2rem;
   border-radius: .8rem;
   margin: 1rem;
 }

.navbar-nav .nav-item .nav-link {
   color: white;
   padding: 0 2rem 0 2rem;
 }
</style>