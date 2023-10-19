<template>
  <div class="wrapper">
    <div class="frame">
      <div>
        <h1 class="title"><b>About us</b></h1>
        <p class="description">
          From the Harmonious union between a mixes of cereals flours and
          legumes flours, a new line of testy specialitiesrich in fiber and
          vegetable proteins is born.
        </p>
      </div>
    </div>
    <div class="img">
      <img id="web" src="../images/about.svg" alt="" />
      <div id="mobile">
        <img src="../images/a-1.svg" alt="">
        <div>
        <h1 class="title"><b>Tasty</b></h1>
        <p class="description">
          Nothing the copy said could convince her and so it didn’t take long.
        </p>
      </div>
        <br>
        <img src="../images/a-2.svg" alt="">
        <div>
        <h1 class="title"><b>Natural</b></h1>
        <p class="description">
          Nothing the copy said could convince her and so it didn’t take long.
        </p>
      </div>
        <br>
        <img src="../images/a-3.svg" alt="">
        <div>
        <h1 class="title"><b>Fresh</b></h1>
        <p class="description">
          Nothing the copy said could convince her and so it didn’t take long.
        </p>
      </div>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: "About",
};
</script>

<style scoped>
.wrapper {
  margin-top: 7rem;
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
.description {
  color: var(--Secondry, #182933);
  text-align: center;
  width: 50%;
  margin: 0 auto;
  font-family: Inter;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 24px; /* 150% */
  letter-spacing: -0.64px;
  opacity: 0.6;
}
.img {
  margin-top: 1rem;
  display: flex;
  width: 100%;
  justify-content: center;
  align-items: center;
}
img {
  width: 1200px;
  height: 100%;
  margin: 0 auto;
}

  #web {
    display: inline;
  }

  #mobile {
    display: none;
  }
@media (max-width: 768px) {
  img {
  width: 100%;
  height: 200px;
  margin: 0 auto;
}
  #web {
    display: none;
  }

  #mobile {
    display: inline;
  }
}
</style>
