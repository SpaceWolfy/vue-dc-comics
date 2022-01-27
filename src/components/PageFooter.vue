<template>
  <footer>
    <!-- Top Footer -->
    <top-footer />
    <!-- Mid Footer -->
    <mid-footer />
    <!-- Spam Section -->
    <spam-section />
  </footer>
</template>

<script>
import TopFooter from "./footer/TopFooter.vue";
import MidFooter from "./footer/MidFooter.vue";
import SpamSection from "./footer/SpamSection.vue";

export default {
  components: { SpamSection },
  TopFooter,
  MidFooter,
  SpamSection,
};
</script>

<style lang="scss" scoped></style>
