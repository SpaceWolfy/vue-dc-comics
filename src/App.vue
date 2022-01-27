<template>
  <div id="app">
    <!-- Header (Page) -->
    <header-box />
    <!-- Main Section -->
    <main-section />
    <!-- Footer (Page) -->
    <page-footer />
  </div>
</template>

<script>
import HeaderBox from "./components/HeaderBox.vue";
import MainSection from "./components/MainSection.vue";
import PageFooter from "./components/PageFooter.vue";
export default {
  name: "App",
  components: { HeaderBox, MainSection, PageFooter },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");
#app {
  font-family: Roboto;
}
</style>
