<script setup>
import Button from "./Button.vue";
</script>

<template>
  <div id="carouselExample" class="carousel slide">
    <div class="carousel-inner">
      <!--  -->
      <div class="carousel-item active">
        <img
          src="../images/hero-banner.png"
          class="d-block w-100 carousel-item-img"
          alt="..."
        />
        <div class="carousel-item-inner">
          <h3 class="sub-title">Cookies</h3>
          <h1 class="title">Wheatend Choco Almond</h1>
          <Button />
        </div>
      </div>
      <div class="carousel-item active">
        <img
          src="../images/hero-banner.png"
          class="d-block w-100 carousel-item-img"
          alt="..."
        />
        <div class="carousel-item-inner">
          <h3 class="sub-title">Cookies</h3>
          <h1 class="title">Wheatend Choco Almond</h1>
          <Button />
        </div>
      </div>
      <!--  -->
    </div>
    <!--  -->
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselExample"
      data-bs-slide="prev"
    >
      <div class="carousel-control-icons">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </div>
    </button>
    <!--  -->
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselExample"
      data-bs-slide="next"
    >
      <div class="carousel-control-icons">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </div>
    </button>
  </div>
</template>

<style scoped>
.carousel {
  display: flex;
  margin-top: 30px !important;
  width: full;
  height: 498px;
  flex-direction: column;
  align-items: center;
  width: 1400px;
  margin: 0 auto;
  gap: 40px;
  flex-shrink: 0;
}
.carousel-inner {
  border-radius: 30px;
  width: 1200px;
  height: 498px;
}
.carousel-item {
  position: relative;
  width: 1200px;
  height: 498px;
  border-radius: 30px;
  overflow: hidden;
}
.carousel-item-inner {
  width: 574px !important;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: fit-content;
  margin-left: 120px;
}

.sub-title {
  font-family: Falidasi Triasie;
  font-size: 60px;
  font-style: normal;
  font-weight: 400;
  line-height: 100px; /* 166.667% */
  letter-spacing: -1.2px;
  background: linear-gradient(122deg, #393230 13.07%, #f99e58 85.97%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.title {
  color: #060029;
  font-family: Cambon;
  font-size: 94px;
  font-style: normal;
  font-weight: 400;
  line-height: 88px; /* 93.617% */
  letter-spacing: -3.76px;
}
.carousel-item-img {
  position: absolute;
  /* opacity: 0.5; */
  z-index: -10;
}
.carousel-control-icons {
  background-color: #fff;
  height: 50px;
  width: 50px;
  padding: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
.carousel-control-next {
  opacity: 1;
}
.carousel-control-prev {
  opacity: 1;
}
.carousel-control-next-icon {
  background-image: url("https://upload.wikimedia.org/wikipedia/commons/2/24/Arrow-right-512.png");
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center;
  width: 20px;
  height: 20px;
}
.carousel-control-prev-icon {
  background-image: url("https://cdn-icons-png.flaticon.com/512/109/109618.png");
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center;
  width: 20px;
  height: 20px;
}
</style>

<script>
export default {
  name: "Hero",
};
</script>
