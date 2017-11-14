<template>
<div class="jumbotron-fluid text-center">
    <h1 class="display-2">Charity Revolutionized. Earn reward Token by Donating</h1>
    <p class="lead display-4">No fees. No transaction cost. Powered by the STEEM Blockchain.</p>
    <p class="lead">
      <a class="btn btn-danger btn-lg" href="#" role="button">DONATE</a>
    </p>
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
  .jumbotron-fluid {
    background: url("../assets/hero-bg.png") no-repeat center;
    background-size: cover;
    min-height: 76rem;
  }

  .display-2 {
    padding-top: 15%;
    color: #FF7575;
    font-weight: bold;
  }

  .display-4 {
    color: #FF7575;
    margin-top: 4rem;
  }

  .btn {
    margin-top: 15rem;
    padding: 1rem 5rem;
    border-radius: 0.8rem;
    font-size: 2.5rem;
  }
</style>