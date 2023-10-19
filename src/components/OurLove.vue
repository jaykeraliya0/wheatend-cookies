<script setup></script>

<template>
  <div className="frame">
    <div className="div">
      <div className="text-wrapper"><b>Our Love's</b></div>
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
.text-wrapper {
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
  max-width: 592px;
  width: 100%;
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
  max-width: 387px;
  width: 100%;
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
  max-width: 388px;
  width: 100%;
}

.frame .div-5 {
  border: 1px solid #e5e5e5;
  border-radius: 24px;
  height: 181px;
  overflow: hidden;
  position: relative;
  max-width: 388px;
  width: 100%;
}

.frame .overlap-group {
  height: 181px;
  left: 0;
  position: absolute;
  top: 0;
  max-width: 136px;
  width: 100%;
}

.frame .rectangle {
  background-color: #007ea5;
  box-shadow: inset 0px 4px 34px 20px #1c4c6740;
  height: 181px;
  left: 0;
  position: absolute;
  top: 0;
  max-width: 100px;
  width: 100%;
}

.frame .element-s-qm-PC {
  height: 147px;
  left: 50px;
  position: absolute;
  top: 21px;
  max-width: 86px;
  width: 100%;
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
  max-width: 100px;
  width: 100%;
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
  max-width: 100px;
  width: 100%;
}

.frame .overlap {
  height: 181px;
  left: 0;
  position: absolute;
  top: 0;
  max-width: 139px;
  width: 100%;
}

.frame .rectangle-4 {
  background-color: #4a3791;
  box-shadow: inset 0px 4px 34px 20px #1c4c6740;
  height: 181px;
  left: 0;
  position: absolute;
  top: 0;
  max-width: 100px;
  width: 100%;
}

.frame .element-edr-s-qm-z-PC {
  height: 133px;
  left: 53px;
  position: absolute;
  top: 28px;
  max-width: 86px;
  width: 100%;
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
  max-width: 1440px;
  width: 100%;
  flex-direction: column;
  align-items: center;
  gap: 40px;
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
@media (max-width: 1440px) {
  .div-2 {
    width: 100%;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .img {
    width: 100%;
    height: auto;
    margin: 0 auto;
  }
  .div-3 {
    width: 100%;
    /* flex-direction: column; */
    align-items: center;
    justify-content: center;
  }
  .div-4 {
    width: 100%;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .div-5 {
    width: 100%;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
}
@media (max-width: 768px) {
  .div-3 {
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .div-4 {
    margin: 0 auto;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
}
</style>

<script>
export default {
  name: "OurLove",
};
</script>
