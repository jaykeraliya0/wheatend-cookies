<script setup></script>

<template>
  <div class="wrapper">
    <div class="title">
      <h1>Limited time <span> Offer's </span></h1>
      <div class="description">
        <p>
          From the Harmonious union between a mixes of cereals flours and
          legumes flours, a new line of testy specialitiesrich in fiber and
          vegetable proteins is born.
        </p>
      </div>
      <div class="time">
        05
        <span> : </span>
        45
        <span> : </span>
        59
      </div>
    </div>
    <div id="carouselExample2" class="carousel slide">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="../images/offer.png"
            class="d-block w-100 carousel-item-img"
            alt="../images/offer.png"
          />
        </div>
        <div class="carousel-item">
          <img
            src="../images/offer.png"
            class="d-block w-100 carousel-item-img"
            alt="../images/offer.png"
          />
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExample2"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExample2"
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
  width: 100%;
  margin: 7rem auto;
  padding: 5rem;
  background: #1c0b03;
  background: linear-gradient(
    to bottom,
    #1c0b03 0%,
    #1c0b03 63%,
    #fff 63%,
    #fff 100%
  );
  color: #fff;
  background-size: cover;
  display: flex;
  flex-direction: column;
}
.title {
  width: 100%;
  max-width: 600px;
  margin: 0 auto;
  text-align: center;
}
.title h1 {
  color: #fff;
  text-align: center;
  font-family: Cambon;
  font-size: 44px;
  font-style: normal;
  font-weight: 250;
  line-height: 46px; /* 104.545% */
}
.title h1 span {
  color: #ffd600;
  text-align: center;
  font-family: Cambon;
  font-size: 54px;
  font-style: normal;
  font-weight: 400;
  line-height: 46px; /* 85.185% */
}
.description {
  width: 100%;
  max-width: 600px;
  margin: 0 auto;
  text-align: center;
  margin-top: 2rem;
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
.carousel {
  margin: 5rem auto;
  z-index: 10;
  display: flex;
  max-width: 793px !important;
  width: 100%;
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
  /* max-height: 450px; */
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
  box-shadow: 0px 4px 44px 0px rgba(0, 0, 0, 0.06);
  opacity: 1;
}
.carousel-control-prev {
  left: -43px;
}
.carousel-control-next {
  right: -43px;
}
@media (max-width: 768px) {
  .carousel {
    margin: 5rem auto;
    z-index: 10;
    display: flex;
    max-width: 793px !important;
    width: 100%;
    height: 365px;
    padding-right: 0px;
    align-items: center;
    flex-shrink: 0;
    border-radius: 24px;
    max-height: 210px;
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
    width: 46px;
    height: 46px;
    flex-shrink: 0;
    border-radius: 46px;
    background: linear-gradient(0deg, #1c0b03 0%, #1c0b03 100%), #fff;
    box-shadow: 0px 4px 44px 0px rgba(0, 0, 0, 0.06);
    opacity: 1;
  }
  .carousel-control-prev {
    left: -21px;
  }
  .carousel-control-next {
    right: -21px;
  }
}
</style>

<script>
export default {
  name: "Offer",
};
</script>
