<template>
  <header>
    <nav class="navigation-bar">
      <div class="dc-logo">
        <img src="@/assets/img/dc-logo.png" alt="" />
      </div>
      <ul>
        <li v-for="(navbtn, index) in nav" :key="index">
          <a :href="navbtn.link">{{ navbtn.title }}</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  props: {
    nav: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "@/style/var.scss";

header {
  height: 110px;
  display: $display-f;

  .navigation-bar {
    width: 100%;
    display: $display-f;
    justify-content: space-around;
    align-items: center;

    .dc-logo > img {
      width: 75px;
    }

    ul {
      font-size: 12px;
      font-weight: 600;

      li {
        padding: 46px 0px;
        margin: 0 17px;
        border-bottom: 4px solid transparent;

        &:hover {
          border-bottom: 4px solid $dc-blue;
        }

        &:hover a {
          color: $dc-blue;
        }

        a {
          text-decoration: none;
          color: #504c50;
        }
      }
    }
  }
}
</style>
