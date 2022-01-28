<template>
  <div class="black-bar">
    <div class="container">
      <div class="ad-series">CURRENT SERIES</div>
      <div v-for="(comic, index) in cards" :key="index" class="comic-card">
        <div class="card-img">
          <img :src="comic.thumb" alt="" />
        </div>
        <div class="title">{{ comic.series }}</div>
      </div>

      <div class="load">LOAD MORE</div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    cards: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "@/style/var.scss";

.black-bar {
  background-color: #1c1c1c;
  color: white;

  .container {
    margin: 0 auto;
    width: 1280px;
    display: $display-f;
    justify-content: center;
    flex-wrap: wrap;
    position: relative;

    .ad-series,
    .load {
      background-color: $dc-blue;
      text-align: center;
      font-weight: 600;
    }

    .ad-series {
      padding: 15px 30px;
      font-size: 25px;
      position: absolute;
      left: 0;
      top: -35px;
    }

    .load {
      margin-bottom: 20px;
      padding: 12px 60px;
      font-size: 12px;
    }

    .comic-card {
      width: 180px;
      margin: 50px 15px;

      .card-img {
        height: 180px;
        width: 100%;

        img {
          height: 100%;
          width: 100%;
          object-position: top;
          object-fit: cover;
        }
      }

      .title {
        margin-top: 20px;
      }
    }
  }
}
</style>
