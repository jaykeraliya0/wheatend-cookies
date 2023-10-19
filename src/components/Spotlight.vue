<template>
  <div class="wrapper">
    <div>
      <h1 class="title"><b>Spotlight</b></h1>
      <p class="description">
        From the Harmonious union between a mixes of cereals flours and legumes
        flours, a new line of testy specialitiesrich in fiber and vegetable
        proteins is born.
      </p>
    </div>
    <div class="main">
      <div class="ima">
        <img src="../images/spotlight.png" alt="" />
      </div>
      <div class="cards">
        <div class="card">
          <img src="../images/pinapple.png" alt="" />
          <div class="data">
            <div class="name">
              <b>
                <p>Pineapple Cookie</p>
                <p class="price">₹299.00 <span>₹559.00</span></p>
              </b>
            </div>
            <div class="btnc">
              <button>Buy&nbsp;Now</button>
            </div>
          </div>
        </div>
        <div class="card">
          <img src="../images/pinapple.png" alt="" />
          <div class="data">
            <div class="name">
              <p>Pineapple Cookie</p>
              <p class="price">₹299.00 <span>₹559.00</span></p>
            </div>
            <div class="btnc">
              <button>Buy&nbsp;Now</button>
            </div>
          </div>
        </div>
        <div class="card">
          <img src="../images/pinapple.png" alt="" />
          <div class="data">
            <div class="name">
              <p>Pineapple Cookie</p>
              <p class="price">₹299.00 <span>₹559.00</span></p>
            </div>
            <div class="btnc">
              <button>Buy&nbsp;Now</button>
            </div>
          </div>
        </div>
        <div class="vm">
          <button>
            View more
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="21"
              height="21"
              viewBox="0 0 21 21"
              fill="none"
            >
              <g id="vuesax/outline/arrow-right">
                <g id="arrow-right">
                  <path
                    id="Vector"
                    d="M12.8827 15.8754C12.7243 15.8754 12.566 15.8171 12.441 15.6921C12.1993 15.4504 12.1993 15.0504 12.441 14.8088L17.0577 10.1921L12.441 5.57545C12.1993 5.33378 12.1993 4.93378 12.441 4.69211C12.6827 4.45045 13.0827 4.45045 13.3243 4.69211L18.3827 9.75045C18.6244 9.99211 18.6244 10.3921 18.3827 10.6338L13.3243 15.6921C13.1993 15.8171 13.041 15.8754 12.8827 15.8754Z"
                    fill="#292D32"
                  />
                  <path
                    id="Vector_2"
                    d="M17.7984 10.8171H3.77344C3.43177 10.8171 3.14844 10.5338 3.14844 10.1921C3.14844 9.85047 3.43177 9.56714 3.77344 9.56714H17.7984C18.1401 9.56714 18.4234 9.85047 18.4234 10.1921C18.4234 10.5338 18.1401 10.8171 17.7984 10.8171Z"
                    fill="#292D32"
                  />
                </g>
              </g>
            </svg>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  margin: 0 auto;
  margin-top: 7rem;
  max-width: 1200px;
  width: 100%;
  height: 100%;
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
.main {
  display: flex;
  max-width: 1200px;
  width: 100%;
  height: 428px;
}
.ima img {
  max-width: 283px;
  width: 100%;
  /* height: 329px; */
  flex-shrink: 0;
  border-radius: 24px;
}
.cards {
  display: inline-flex;
  flex-wrap: wrap;
  align-items: center;
  /* gap: 0 48.441px; */
  margin-top: 5rem;
}
.card {
  width: calc(100% / 3);
  padding-left: 48.441px;
  background: transparent !important;
  border: none;
}
.card img {
  width: 100%;
  height: 235px;
  border-radius: 24px;
  background: #eceae9;
}
.card .data {
  display: flex;
  margin-top: 1rem;
  justify-content: space-between;
  gap: 1rem;
}
.card .data .name p {
  color: #000;
  font-family: Cambon;
  font-size: 20px;
  font-style: normal;
  font-weight: 600;
  line-height: normal;
  letter-spacing: -0.4px;
}
.card .data .name .price {
  color: #000;
  font-family: Inter;
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  letter-spacing: -1.6px;
}
.card .data .name .price span {
  color: #000;
  font-family: Inter;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  letter-spacing: -0.42px;
  text-decoration: line-through;
  opacity: 0.4;
  margin-left: 2px;
}
.btnc button {
  display: flex;
  padding: 10px 12px;
  justify-content: center;
  align-items: center;
  gap: 6px;
  border-radius: 8px;
  background: var(--yellow-pri, #fddc2e);
  word-wrap: normal;
  outline: none;
  border: none;
}
.vm {
  width: 100%;
  display: flex;
  justify-content: center;
}
.vm button {
  display: flex;
  padding: 14px 16px;
  justify-content: center;
  align-items: center;
  gap: 6px;
  border-radius: 8px;
  border: 1px solid #e6e6e6;
}
@media (max-width: 967px) {
  .wrapper {
    margin-top: 3rem;
  }
  .title {
    font-size: 40px;
    line-height: 60px;
    padding: 0 2rem;
  }
  .description {
    width: 100%;
    font-size: 14px;
    line-height: 21px;
  }
  .main {
    flex-direction: column;
    height: auto;
  }
  .ima {
    width: 100%;
    display: flex;
    justify-content: center;
    margin-top: 2rem;
  }
  .ima img {
    max-width: 400px;
    width: 100%;
    height: 100%;
    border-radius: 24px;
  }

  .cards {
    margin-top: 2rem;
    gap: 1.25rem;
  }
  .card {
    width: calc(100% / 2 - 3rem);
    padding-left: 0px;
    margin-bottom: 2rem;
    margin-right: 1rem;
    margin-left: 1rem;
  }
  .card img {
    width: 100%;
    height: 100%;
    border-radius: 24px;
  }
  .card .data {
    flex-direction: column;
    margin-top: 1rem;
  }
  .card .data .name p {
    font-size: 16px;
    line-height: 24px;
  }
  .card .data .name .price {
    font-size: 16px;
    line-height: 24px;
  }
  .card .data .name .price span {
    font-size: 12px;
    line-height: 18px;
  }
  .btnc button {
    padding: 8px 10px;
    width: 100%;
  }
  .vm {
    width: 100%;
    display: flex;
    justify-content: center;
  }
  .vm button {
    padding: 10px 12px;
  }
}
</style>
<script>
export default {
  name: "Spotlight",
};
</script>
