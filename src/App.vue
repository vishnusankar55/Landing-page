<template>
  <div>
    <Homenav/>
    <Home/>
  </div>
</template>

<script>
  import Homenav from "./components/Homenav.vue"
  import Home from "./components/Home.vue"
  export default {
    name: "App",
    components: {
      Homenav,
      Home
    }
  };

</script>

<style>
</style>