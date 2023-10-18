<script setup></script>

<template>
  <div class="wrapper">
    <!--  -->
    <div class="titleWrapper">
      <h1 class="title">Our Love's</h1>
      <div class="descriptionWrapper">
        <p class="description">
          From the Harmonious union between a mixes of cereals flours and
          legumes flours, a new line of testy specialitiesrich in fiber and
          vegetable proteins is born.
        </p>
      </div>
    </div>
    <!--  -->
    <div class="cardWrapper">
      <div class="flavours"></div>
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  display: flex;
  width: 1440px;
  flex-direction: column;
  align-items: center;
  gap: 40px;
}
.title {
  text-align: center;
  font-family: Cambon;
  font-size: 60px;
  font-style: normal;
  font-weight: 400;
  line-height: 90px; /* 150% */
  letter-spacing: -1.2px;
  background: linear-gradient(122deg, #393230 13.07%, #f99e58 85.97%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.descriptionWrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 10px;
  align-self: stretch;
}
.description {
  width: 592px;
  color: var(--Secondry, #182933);
  text-align: center;
  font-family: Inter;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 24px; /* 150% */
  letter-spacing: -0.64px;
  opacity: 0.6;
}
.cardWrapper {
  display: flex;
  align-items: flex-start;
  gap: 18px;
}
.flavours {
  width: 387px;
  height: 382px;
  border-radius: 24px;
  background: #fff;
}
</style>

<script>
export default {
  name: "OurLove",
};
</script>
