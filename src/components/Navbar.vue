<template>
<div>
  <nav class="navbar navbar-expand-lg navbar-light">
    <a class="navbar-brand" href="#">
      <img src="../assets/DCT.svg" width="82" height="71" alt="Dochato Logo">
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
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

 .navbar {
   background: #FDFDFD;
 }

 .nav-link {
   border: #808080 solid .2rem;
   border-radius: .8rem;
   margin: 1rem;
 }

.navbar-nav .nav-item .nav-link {
   color: #808080;
   padding: 0 2rem 0 2rem;
 }
</style>