<template>
  <div class="top-footer">
    <ul>
      <li>
        <img src="@/assets/img/comics.png" alt="" />
        DIGITAL COMICS
      </li>
      <li><img src="@/assets/img/merchandise.png" alt="" />DC MERCHANDISE</li>
      <li><img src="@/assets/img/subscription.png" alt="" />SUBSCRIPTION</li>
      <li><img src="@/assets/img/shop.png" alt="" />COMIC SHOP LOCATOR</li>
      <li>
        <img class="svg-img" src="@/assets/img/visa.svg" alt="" />DC POWER VISA
      </li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "@/style/var.scss";

.top-footer {
  height: 160px;
  width: 100%;
  background-color: $dc-blue;
  display: $display-f;
  justify-content: center;
  align-items: center;

  ul {
    li {
      display: $display-f;
      align-items: center;
      color: white;
      font-size: 15px;
      padding: 40px;

      img {
        height: 55px;
        margin-right: 16px;
      }

      .svg-img {
        width: 55px;
      }
    }
  }
}
</style>
