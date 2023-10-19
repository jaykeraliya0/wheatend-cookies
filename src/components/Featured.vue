<template>
  <div class="frame">
    <div class="div">
      <img class="img-2" alt="Frame" src="../images/f-1.svg" />
      <div class="div-2">
        <div class="text-wrapper-2">Top Brands</div>
        <div class="text-wrapper-3">With Crazy Deals!</div>
      </div>
    </div>
    <div class="div">
      <img class="img-2" alt="Frame" src="../images/f-2.svg" />
      <div class="div-2">
        <div class="text-wrapper-2">Pan India Delivery</div>
        <div class="text-wrapper-3">3-5 Weekdays</div>
      </div>
    </div>
    <div class="div">
      <img class="class" alt="Frame" src="../images/f-3.svg" />
      <div class="div-3">
        <div class="text-wrapper-2">Free Returns</div>
        <p class="text-wrapper-3">Free Pickup within 48 hours</p>
      </div>
    </div>
    <div class="div">
      <img class="class" alt="Frame" src="../images/f-4.svg" />
      <div class="div-2">
        <div class="text-wrapper-2">Customer Support</div>
        <div class="text-wrapper-4">Support@wheatend.com</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Featured",
};
</script>

<style scoped>
.frame {
  background-color: #f4f4f4;
  margin: 0 auto;
  align-items: center;
  display: flex;
  gap: 31px;
  position: relative;
  width: 1200px;
}

.frame .div {
  align-items: center;
  display: flex;
  flex: 1;
  flex-grow: 1;
  gap: 22px;
  padding: 10px;
  position: relative;
}

.frame .class {
  height: 40px;
  position: relative;
  width: 40px;
}

.frame .group {
  height: 38px;
  left: 7px;
  position: relative;
  top: 1px;
  width: 28px;
}

.frame .overlap-group {
  height: 38px;
  position: relative;
  width: 26px;
}

.frame .union {
  height: 1px;
  left: 8px;
  position: absolute;
  top: 12px;
  width: 1px;
}

.frame .img {
  height: 1px;
  left: 16px;
  position: absolute;
  top: 12px;
  width: 1px;
}

.frame .vector {
  height: 17px;
  left: 4px;
  position: absolute;
  top: 4px;
  width: 17px;
}

.frame .vector-2 {
  height: 38px;
  left: 0;
  position: absolute;
  top: 0;
  width: 26px;
}

.frame .text-wrapper {
  color: #000000;
  font-family: "Roboto-Bold", Helvetica;
  font-size: 9px;
  font-weight: 700;
  left: 10px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 8px;
  white-space: nowrap;
  width: 5px;
}

.frame .div-2 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 4px;
  position: relative;
}

.frame .text-wrapper-2 {
  color: #000000;
  font-family: "Cambon-Regular", Helvetica;
  font-size: 20px;
  font-weight: 400;
  letter-spacing: 0;
  line-height: normal;
  margin-top: -1px;
  position: relative;
  text-align: center;
  width: fit-content;
}

.frame .text-wrapper-3 {
  color: #000000;
  font-family: "Inter-Regular", Helvetica;
  font-size: 16px;
  font-weight: 400;
  letter-spacing: 0;
  line-height: normal;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.frame .img-2 {
  height: 48px;
  position: relative;
  width: 48px;
}

.frame .div-3 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 4px;
  margin-right: -16.25px;
  position: relative;
}

.frame .text-wrapper-4 {
  color: #000000;
  font-family: "Inter-Regular", Helvetica;
  font-size: 16px;
  font-weight: 400;
  letter-spacing: 0;
  line-height: normal;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}
@media (max-width: 1200px) {
  .frame {
    flex-direction: column;
    width: 100%;
  }
  .frame .div {
    flex-direction: column;
    width: 100%;
  }
  .frame .div-2 {
    align-items: center;
    margin-top: 10px;
    width: 100%;
  }
  .frame .div-3 {
    align-items: center;
    margin-top: 10px;
    width: 100%;
  }
  .frame .img-2 {
    margin: 0 auto;
  }
  .frame .text-wrapper-2 {
    margin: 0 auto;
  }
  .frame .text-wrapper-3 {
    margin: 0 auto;
  }
  .frame .text-wrapper-4 {
    margin: 0 auto;
  }
}
</style>
