<script setup></script>

<!-- <template>
  <div class="wrapper">
  
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
    
    <div class="cardWrapper">
      <div class="flavours"></div>
    </div>
  </div>
</template> -->

<template>
  <div className="frame">
    <div className="div">
      <div className="text-wrapper"><b>Our Love’s</b></div>
      <p className="p">
        From the Harmonious union between a mixes of cereals flours and legumes
        flours, a new line of testy specialitiesrich in fiber and vegetable
        proteins is born.
      </p>
    </div>
    <div className="div-2">
      <img
        className="img"
        alt="Frame"
        src="../images/love-main.png"
        style="border-radius: 28px; overflow: hidden"
      />
      <div className="div-3">
        <div className="div-4">
          <div className="div-5">
            <div className="overlap-group">
              <div className="rectangle" />
              <img
                className="element-s-qm-PC"
                alt="Element s qm PC"
                src="../images/p-2.png"
              />
              <div className="text-wrapper-2">Taste it!</div>
            </div>
            <div className="div-6">
              <div className="text-wrapper-3"><b>Cookies</b></div>
              <div className="text-wrapper-4">Creamy Butter Cookies</div>
            </div>
          </div>
          <div className="div-5">
            <div className="overlap-group">
              <div className="rectangle-2" />
              <img
                className="element-s-qm-PC"
                alt="Element s qm PC"
                src="../images/p-1.png"
              />
              <div className="text-wrapper-5">Love it!</div>
            </div>
            <div className="div-6">
              <div className="text-wrapper-3"><b>Kesar Badam</b></div>
              <div className="text-wrapper-4">Creamy Butter Cookies</div>
            </div>
          </div>
        </div>
        <div className="div-4">
          <div className="div-5">
            <div className="overlap-group">
              <div className="rectangle-3" />
              <img
                className="element-s-qm-PC"
                alt="Element s qm PC"
                src="../images/p-3.png"
              />
              <div className="text-wrapper-2">Taste it!</div>
            </div>
            <div className="div-6">
              <div className="text-wrapper-3"><b>Almond</b></div>
              <div className="text-wrapper-4">Creamy Butter Cookies</div>
            </div>
          </div>
          <div className="div-5">
            <div className="overlap">
              <div className="rectangle-4" />
              <img
                className="element-edr-s-qm-z-PC"
                alt="Element s qm PC"
                src="../images/p-4.png"
              />
              <div className="text-wrapper-6">It Heaven!</div>
            </div>
            <div className="div-6">
              <div className="text-wrapper-3"><b>Pistachio</b></div>
              <div className="text-wrapper-4">Creamy Butter Cookies</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.frame {
  align-items: center;
  display: flex;
  flex-direction: column;
  gap: 40px;
  position: relative;
  max-width: 1440px;
  margin: 0 auto;
}

.frame .div {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 10px;
  position: relative;
  width: 100%;
}

.frame .text-wrapper {
  -webkit-background-clip: text !important;
  -webkit-text-fill-color: transparent;
  -webkit-text-stroke: 0.5px transparent;
  align-self: stretch;
  background: linear-gradient(
    180deg,
    rgb(56.62, 50.24, 47.51) 0%,
    rgb(249, 158, 88) 100%
  );
  background-clip: text;
  background-image: linear-gradient(
    180deg,
    rgb(56.62, 50.24, 47.51) 0%,
    rgb(249, 158, 88) 100%
  );
  color: transparent;
  font-family: "Cambon-Regular", Helvetica;
  font-size: 60px;
  font-weight: 400;
  letter-spacing: -1.2px;
  line-height: 90px;
  margin-left: -0.5px;
  margin-top: -1.5px;
  position: relative;
  text-align: center;
  text-fill-color: transparent;
}

.frame .p {
  color: var(--secondry);
  font-family: "Inter-Regular", Helvetica;
  font-size: 16px;
  font-weight: 400;
  letter-spacing: -0.64px;
  line-height: 24px;
  opacity: 0.6;
  position: relative;
  text-align: center;
  width: 592px;
}

.frame .div-2 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 18px;
  position: relative;
}

.frame .img {
  height: 382px;
  position: relative;
  width: 387px;
}

.frame .div-3 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 19px;
  position: relative;
}

.frame .div-4 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  gap: 20px;
  position: relative;
  width: 388px;
}

.frame .div-5 {
  border: 1px solid #e5e5e5;
  border-radius: 24px;
  height: 181px;
  overflow: hidden;
  position: relative;
  width: 388px;
}

.frame .overlap-group {
  height: 181px;
  left: 0;
  position: absolute;
  top: 0;
  width: 136px;
}

.frame .rectangle {
  background-color: #007ea5;
  box-shadow: inset 0px 4px 34px 20px #1c4c6740;
  height: 181px;
  left: 0;
  position: absolute;
  top: 0;
  width: 100px;
}

.frame .element-s-qm-PC {
  height: 147px;
  left: 50px;
  position: absolute;
  top: 21px;
  width: 86px;
}

.frame .text-wrapper-2 {
  /* -webkit-text-stroke: 0.63px #000000; */
  color: #ffffff33;
  font-family: "Cambon-ExtraBold", Helvetica;
  font-size: 30px;
  font-weight: 800;
  left: -31px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 70px;
  transform: rotate(-90deg);
}

.frame .div-6 {
  align-items: center;
  display: inline-flex;
  flex-direction: column;
  gap: 4px;
  left: 147px;
  position: absolute;
  top: 48px;
}

.frame .text-wrapper-3 {
  color: #007ea5;
  font-family: "Cambon-Regular", Helvetica;
  font-size: 36px;
  font-weight: 400;
  letter-spacing: -0.72px;
  line-height: 48px;
  margin-top: -1.37px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.frame .text-wrapper-4 {
  color: var(--secondry);
  font-family: "Inter-Regular", Helvetica;
  font-size: 21.9px;
  font-weight: 400;
  letter-spacing: -0.88px;
  line-height: 32.9px;
  opacity: 0.6;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.frame .rectangle-2 {
  background-color: #9cb035;
  box-shadow: inset 0px 4px 34px 20px #1c4c6740;
  height: 181px;
  left: 0;
  position: absolute;
  top: 0;
  width: 100px;
}

.frame .text-wrapper-5 {
  /* -webkit-text-stroke: 0.63px #000000; */
  color: #ffffff33;
  font-family: "Cambon-ExtraBold", Helvetica;
  font-size: 30px;
  font-weight: 800;
  left: -27px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 70px;
  transform: rotate(-90deg);
}

.frame .rectangle-3 {
  background-color: #3b2c1a;
  box-shadow: inset 0px 4px 34px 20px #1c4c6740;
  height: 181px;
  left: 0;
  position: absolute;
  top: 0;
  width: 100px;
}

.frame .overlap {
  height: 181px;
  left: 0;
  position: absolute;
  top: 0;
  width: 139px;
}

.frame .rectangle-4 {
  background-color: #4a3791;
  box-shadow: inset 0px 4px 34px 20px #1c4c6740;
  height: 181px;
  left: 0;
  position: absolute;
  top: 0;
  width: 100px;
}

.frame .element-edr-s-qm-z-PC {
  height: 133px;
  left: 53px;
  position: absolute;
  top: 28px;
  width: 86px;
}

.frame .text-wrapper-6 {
  /* -webkit-text-stroke: 0.63px #000000; */
  color: #ffffff33;
  font-family: "Cambon-ExtraBold", Helvetica;
  font-size: 30px;
  font-weight: 800;
  left: -49px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 69px;
  transform: rotate(-90deg);
}

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
