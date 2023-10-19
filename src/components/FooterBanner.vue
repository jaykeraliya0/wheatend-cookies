<template>
  <div class="wrapper">
    <div class="footer-banner">
      <img src="../images/footer-banner.png" alt="" />
      <img class="mini" src="../images/footer-banner-mini.png" alt="" />
      <div class="frame">
        <div class="text">
          <h1>
            Get Your Special,
            <span>Offers & Coupons</span>
          </h1>
        </div>
        <form action="">
          <input
            type="text"
            name="email"
            id="email"
            placeholder="Your email address"
          />
          <button type="submit">Subscribe</button>
        </form>
      </div>
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  width: 100%;
  height: 100%;
  background: rgba(255, 255, 255, 0);
  background: linear-gradient(
    to bottom,
    rgba(255, 255, 255, 0) 0%,
    rgba(255, 255, 255, 0) 35%,
    rgba(0, 0, 0, 1) 35%,
    rgba(0, 0, 0, 1) 100%
  );
  padding: 3rem;
}
.mini {
  display: none;
}
.footer-banner {
  position: relative;
  max-width: 1200px;
  width: 100%;
  height: 400px;
  flex-shrink: 0;
  border-radius: 15px;
  margin: 0 auto;
  margin-top: 5rem;
  background: #fff;
}
.footer-banner img {
  position: absolute;
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 15px;
}
.frame {
  position: relative;
  display: flex;
  flex-direction: column;
  max-width: 438px;
  width: 100%;
  height: 100%;
  justify-content: center;
  padding-left: 4rem;
  z-index: 10;
}
.footer-banner .text {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  margin-top: 40px;
}
.footer-banner .text h1 {
  color: var(--dark-1, #16182f);
  font-family: Cambon;
  font-size: 44px;
  font-style: normal;
  font-weight: 400;
  line-height: 54px; /* 122.727% */
  letter-spacing: -0.44px;
  align-self: stretch;
}
.footer-banner .text h1 span {
  font-family: Cambon;
  font-size: 44px;
  font-style: normal;
  font-weight: 700;
  line-height: 54px; /* 122.727% */
  letter-spacing: -0.44px;
  background: linear-gradient(122deg, #393230 13.07%, #f99e58 85.97%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.footer-banner form {
  display: flex;
  align-items: center;
  margin-top: 40px;
  gap: 8px;
}
.footer-banner form input {
  display: flex;
  padding: 10px 6px 10px 12px;
  align-items: center;
  gap: 10px;
  flex: 1 0 0;
  border-radius: 8px;
  background: #f2f2f2;
  border: none;
  outline: none;
  font-family: Inter;
  color: #4c4c4c;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
}
.footer-banner form input::placeholder {
  color: #b4b4b4;
  font-family: Inter;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px; /* 142.857% */
}
.footer-banner form button {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 10px 20px;
  border-radius: 8px;
  gap: 6px;
  border-radius: 8px;
  background: var(--yellow-pri, #fddc2e);
  border: none;
  outline: none;
  font-family: Inter;
  color: #000;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  line-height: 20px; /* 142.857% */
}
@media (max-width: 768px) {
  .wrapper {
    padding: 1.5rem;
  }
  .frame {
    padding: 0 2rem;
  }
}

@media (max-width: 600px) {
  .wrapper {
    padding: 0.5rem;
  }
  .footer-banner {
    height: 600px;
  }
  .frame {
    justify-content: start;
  }
  .mini {
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 400px;
    object-fit: cover;
    border-radius: 15px;
  }
}
</style>
