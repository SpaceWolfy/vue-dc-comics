<template>
  <div class="mid-footer">
    <div class="links-lists">
      <div class="single-list comics-shop">
        <h3>DC COMICS</h3>
        <ul>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>

        <h3>SHOP</h3>
        <ul>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>
      </div>

      <div class="single-list">
        <h3>DC</h3>
        <ul>
          <li>Terms Of Use</li>
          <li>Privacy policy (New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>
      </div>

      <div class="single-list">
        <h3>SITES</h3>
        <ul>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>
    </div>
    <img class="logo-bg" src="@/assets/img/dc-logo-bg.png" alt="" />
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "@/style/var.scss";

.mid-footer {
  background: url("../../assets/img/footer-bg.jpg") no-repeat;
  height: 380px;
  background-size: cover;
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 0 120px;

  .logo-bg {
    height: 575px;
  }

  .links-lists {
    display: $display-f;
    margin-bottom: 30px;

    h3 {
      margin: 18px 0;
      color: white;
    }

    ul {
      flex-direction: column;
      color: #838689;

      li {
        font-size: 12px;
        margin-top: 5px;
      }
    }

    .single-list {
      margin-right: 40px;
    }

    .comics-shop {
      display: flex;
      flex-direction: column;
    }
  }
}
</style>
