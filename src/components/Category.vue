<script setup>
import Button from "./Button.vue";
</script>

<template>
  <div class="wrapper">
    <div class="title">
      <h1><b>Category's</b></h1>
      <p>Shop by Category</p>
      <div style="margin-top: 28px">
        <Button />
      </div>
    </div>
    <div class="main">
      <div class="card-wrapper">
        <div class="card">
          <div class="fg">
            <img src="../images/cookie-pack-1.png" alt="" />
            <img class="plat" src="../images/cookies-plat.svg" alt="" />
          </div>
          <div class="bg bg-1"><p>Test it!</p></div>
        </div>
        <p class="category">Category #1</p>
      </div>

      <div class="card-wrapper">
        <div class="card">
          <div class="fg">
            <img src="../images/p1.1.png" alt="" />
            <img class="plat" src="../images/cookies-plat.svg" alt="" />
          </div>
          <div class="bg bg-2"><p>Test it!</p></div>
        </div>
        <p class="category">Category #2</p>
      </div>

      <div class="card-wrapper">
        <div class="card">
          <div class="fg">
            <img src="../images/p1.2.png" alt="" />
            <img class="plat" src="../images/cookies-plat.svg" alt="" />
          </div>
          <div class="bg bg-3"><p>Test it!</p></div>
        </div>
        <p class="category">Category #3</p>
      </div>

      <div class="card-wrapper">
        <div class="card">
          <div class="fg">
            <img src="../images/cookie-pack-1.png" alt="" />
            <img class="plat" src="../images/cookies-plat.svg" alt="" />
          </div>
          <div class="bg bg-1"><p>Test it!</p></div>
        </div>
        <p class="category">Category #1</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  display: flex;
  padding: 40px 0px;
  align-items: center;
  gap: 122px;
  width: 1200px;
  margin: 50px auto;
}
.title {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.title h1 {
  text-align: center;
  font-family: Cambon;
  font-size: 60px;
  font-style: normal;
  font-weight: 400;
  line-height: 96px; /* 160% */
  letter-spacing: -1.2px;
  background: linear-gradient(122deg, #393230 13.07%, #f99e58 85.97%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.title p {
  color: var(--Secondry, #182933);
  text-align: center;
  font-family: Inter;
  font-size: 24px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px; /* 150% */
  letter-spacing: -0.96px;
  opacity: 0.6;
}
.category {
  color: var(--Secondry, #182933);
  text-align: center;
  font-family: Inter;
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px; /* 180% */
  letter-spacing: -0.8px;
  opacity: 0.6;
}
.main {
  display: flex;
  align-items: flex-start;
  gap: 45px;
}
.card {
  position: relative;
  width: 181px;
  height: 220px;
  border: none !important;
  background: transparent;
}
.card img {
  width: 100%;
  height: 100%;
  border-radius: 24px;
}
.card-wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 18px;
}
.card .plat {
  position: absolute;
  top: 60%;
  transform: translateY(-25%);
  left: 0;
  z-index: 1;
  width: 100%;
  height: 100%;
}
.fg {
  position: relative;
}
.bg {
  position: absolute;
  bottom: 0;
  display: flex;
  justify-content: end;
  z-index: -1;
  display: flex;
  width: 100%;
  height: 181px;
  flex-direction: column;
  align-items: center;
  flex-shrink: 0;
  border-radius: 30px;
}
.bg p {
  color: rgba(255, 255, 255, 0.2);
  font-family: Cambon;
  font-size: 20px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
}
.bg-1 {
  background: #9cb035;
  box-shadow: 0px 4px 34px 20px rgba(29, 76, 103, 0.25) inset;
}
.bg-2 {
  background: #007ea5;
  box-shadow: 0px 4px 34px 20px rgba(29, 76, 103, 0.25) inset;
}
.bg-3 {
  background: #3c2c1b;
  box-shadow: 0px 4px 34px 20px rgba(29, 76, 103, 0.25) inset;
}
</style>

<script>
export default {
  name: "Category",
};
</script>
