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
import MidFooter from "./footer/MidFooter.vue";
import SpamSection from "./footer/SpamSection.vue";
import TopFooter from "./footer/TopFooter.vue";

export default {
  components: { TopFooter, MidFooter, SpamSection },
};
</script>

<style lang="scss" scoped></style>
