<template>
  <div class="spam-cont">
    <input type="button" value="SIGN-UP NOW!" />
    <nav>
      <h3>FOLLOW US</h3>
      <ul>
        <li>
          <img src="@/assets/img/footer-facebook.png" alt="" />
        </li>
        <li>
          <img src="@/assets/img/footer-twitter.png" alt="" />
        </li>
        <li>
          <img src="@/assets/img/footer-youtube.png" alt="" />
        </li>
        <li>
          <img src="@/assets/img/footer-pinterest.png" alt="" />
        </li>
        <li>
          <img src="@/assets/img/footer-periscope.png" alt="" />
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "@/style/var.scss";

.spam-cont {
  height: 100px;
  background-color: #303030;
  display: flex;
  position: relative;
  justify-content: space-between;
  align-items: center;
  padding: 0 270px;

  input {
    background-color: transparent;
    height: 50px;
    width: 150px;
    font-size: 16px;
    font-weight: 600;
    border: 2px solid $dc-blue;
    color: white;
  }

  nav {
    display: $display-f;
    align-items: center;

    h3 {
      color: $dc-blue;
      margin-right: 30px;
    }

    ul {
      li {
        margin-right: 20px;
      }
    }
  }
}
</style>
