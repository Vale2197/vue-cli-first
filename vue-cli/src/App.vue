<template>
  <div id="app">
    <Title/>
    <hero/>
  </div>
</template>

<script>
/* import HelloWorld from "./components/HelloWorld.vue"; */
import Title from "./components/Title.vue";
import hero from "./components/Hero.vue";

export default {
  name: "App",
  /* components: { */
    /* HelloWorld, */
    components: {
      Title,
      hero
    },
};
</script>

<style lang="scss">
  * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
</style>
