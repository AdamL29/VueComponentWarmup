<template>
  <div id="app">
    <Hero/>
    <Info/>
    <Gallery/>
    <Footers/>
  </div>
</template>

<script>
import Hero from "@/components/ProductHero.vue";
import Info from "@/components/ProductInfo.vue";
import Gallery from "@/components/ProductGallery.vue";
import Footers from "@/components/ProductFooter.vue";

export default {
  name: 'App',
  components: {
    Hero,
    Info,
    Gallery,
    Footers,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
