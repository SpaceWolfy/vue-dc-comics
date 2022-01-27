<template>
  <header>
    <nav class="navigation-bar">
      <div class="dc-logo">
        <img src="@/assets/img/dc-logo.png" alt="" />
      </div>
      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {};
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
      color: #504c50;

      li {
        padding: 46px 0px;
        margin: 0 17px;
        border-bottom: 4px solid transparent;

        &:hover {
          color: $dc-blue;
          border-bottom: 4px solid $dc-blue;
        }
      }
    }
  }
}
</style>
