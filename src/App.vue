<template>
  <div id="app">
  <Navbar></Navbar>
<div class="container">
    <router-view/>
  </div>
  </div>
</template>
<script>
  import Navbar from "./components/Navbar";
  export default {
    components: {Navbar},
    comments: {Navbar}
  }
</script>
<style lang="scss">
@import "~materialize-css/dist/css/materialize.min.css";
</style>
