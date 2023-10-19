<script setup></script>

<template>
  <div class="wrapper">
    <div class="bg">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="1440"
        height="643"
        viewBox="0 0 1440 643"
        fill="none"
      >
        <path
          d="M0 156.5C457.45 -51.5763 982.55 -51.5763 1440 156.5V642.5H0L0 156.5Z"
          fill="#1C0B03"
        />
      </svg>
    </div>
    <div class="title">
      <h1>Limited time <span> Offer's </span></h1>
      <div class="description">
        <p>
          From the Harmonious union between a mixes of cereals flours and
          legumes flours, a new line of testy specialitiesrich in fiber and
          vegetable proteins is born.
        </p>
      </div>
      <!-- <div class="time">
        05
        <span> : </span>
        45
        <span> : </span>
        59
      </div> -->
    </div>
    <div id="carouselExample" class="carousel slide">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="../images/offer.png" class="d-block w-100" alt="../images/offer.png" />
        </div>
        <div class="carousel-item">
          <img src="../images/hero-banner.png" class="d-block w-100" alt="../images/offer.png" />
        </div>
        <div class="carousel-item">
          <img src="../images/love-main.png" class="d-block w-100" alt="../images/offer.png" />
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExample"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExample"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  position: relative;
  width: 100%;
  height: 837px;
  flex-shrink: 0;
  /* background-color: red; */
}
.bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
.bg svg {
  width: 100%;
  height: 100%;
  z-index: -10000;
}
.title {
  margin: 0 auto;
  position: relative;
  color: #fff;
  text-align: center;
  font-family: Cambon;
  font-size: 44px;
  font-style: normal;
  font-weight: 250;
  line-height: 46px; /* 104.545% */
  max-width: 500px;
  padding-top: 12rem;
  z-index: 10000;
}
.title span {
  color: #ffd600;
  text-align: center;
  font-family: Cambon;
  font-size: 54px;
  font-style: normal;
  font-weight: 400;
  line-height: 46px; /* 85.185% */
}
.description {
  color: var(--White, #fff);
  text-align: center;
  font-family: Inter;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 24px; /* 150% */
  letter-spacing: -0.64px;
  opacity: 0.6;
}
.time {
  color: #fff;
  text-align: center;
  font-family: Cambon;
  font-size: 60px;
  font-style: normal;
  font-weight: 600;
  line-height: normal;
  letter-spacing: -1.2px;
}
.time span {
  color: #fff;
  text-align: center;
  font-family: Falidasi Triasie;
  font-size: 50px;
  font-style: italic;
  font-weight: 400;
  line-height: normal;
  letter-spacing: -1.2px;
}
.carousel {
  margin: 7rem auto;
  display: flex;
  width: 793px !important;
  height: 365px;
  padding-right: 0px;
  align-items: center;
  flex-shrink: 0;
  border-radius: 24px;
  box-shadow: 0px 4px 44px 0px rgba(0, 0, 0, 0.06);
}
.carousel-inner {
  position: relative;
  width: 100%;
  height: 100%;
  border-radius: 24px;
}
.carousel-item {
  width: 100%;
  height: 100%;
}
.carousel-item-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 24px;
}
.carousel-control-prev,
.carousel-control-next {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  width: 86px;
  height: 86px;
  flex-shrink: 0;
  border-radius: 86px;
  background: linear-gradient(0deg, #1c0b03 0%, #1c0b03 100%), #fff;
  opacity: 1;
}
.carousel-control-prev {
  left: -43px;
}
.carousel-control-next {
  right: -43px;
}
</style>

<script>
export default {
  name: "Offer",
};
</script>
