<script setup></script>

<template>
   <br>
    <br>
  <div id="web">
    <img  src="../images/our-above.png" alt="" />
    <div class="popularHeading">
      <h2><b>Our Popular Products</b></h2>
      <div>
        From the Harmonious union between a mixes of cereals flours and legumes flours, a new line of testy
        specialitiesrich in fiber and vegetable proteins is born.
      </div>
    </div>
    <img src="../images/our.png" alt="">
  </div>
  <div id="mobile">
    <img src="../images/mobile-popularproduct-above.png" alt="">
    <div class="popularHeading">
      <h2><b>Our Popular Products</b></h2>
      <div>
        From the Harmonious union between a mixes of cereals flours and legumes flours, a new line of testy
        specialitiesrich in fiber and vegetable proteins is born.
      </div>
    </div>
    <img src="../images/mobile-popularproduct.png" alt="">
  </div>
  <br>
    <br>
</template>

<style scoped>
img {
  /* margin: 7rem auto; */
  margin: 0px;
  width: 100%;
  height: 100%;
}

#web {
  display: inline;
}

#mobile {
  display: none;
}
.popularHeading {
    background-color: #1C0B03 !important;
  }

  .popularHeading h2 {

    color: #FFF;
    text-align: center;
    font-family: Cambon;
    font-size: 32px;
    font-style: normal;
    font-weight: 400;
    line-height: 90px;
    /* 281.25% */
    letter-spacing: 0.64px;
  }
  .popularHeading div {
    color: var(--White, #FFF);
    text-align: center;
    font-family: Inter;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 24px;
    /* 150% */
    letter-spacing: -0.64px;
    opacity: 0.6;
  }

@media (max-width: 768px) {

 
  img {
    width: 100%;
    max-height: 800px;
    margin: 0px;
  }

  #web {
    display: none;
  }

  #mobile {
    display: inline;
  }
}
</style>

<script>
export default {
  name: "OurProducts",
};
</script>
