<template>
  <div id="app">
    <!-- Header (Page) -->
    <header-box />
    <!-- Jumbo -->
    <jumbo-series />
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
import JumboSeries from "./components/JumboSeries.vue";
export default {
  name: "App",
  components: { HeaderBox, MainSection, PageFooter, JumboSeries },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");
@import "@/style/main.scss";
#app {
  font-family: Roboto;
}
</style>
