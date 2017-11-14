<template>
  <div class="container-fluid">
  <div class="row text-center">
    <div class="col-sm left">
      One of three columns
    </div>
    <div class="col-sm right">
      One of three columns
    </div>
   </div> <!-- End Row -->
  </div>  <!-- End Container -->
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
 .container-fluid {
   padding-top: 2rem;
   };

  .col-sm{
    color: green;
  }
</style>