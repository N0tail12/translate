<template>
  <div id="app">
    <HomeViewVue />
  </div>
</template>

<script>
import HomeViewVue from "./views/HomeView.vue";
export default {
  components: { HomeViewVue }
};
</script>

<style>
#app {
  max-width: 100vw;
}
</style>
