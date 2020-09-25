<template>
  <b-container class="advantages">
    <div class="container">
      <div class="advantages__inner">
        <h2 class="advantages__title">
          Our
          <span class="text-red">&ensp;Advantages</span>
        </h2>
        <div class="advantages__items">
          <div class="advantages-card">
            <div class="advantages-card__inner">
              <div class="advantages-card-img">
                <div class="advantages-card-img__inner">
                  <img src="public\img\quote-right.svg" alt="quote-right" />
                </div>
              </div>
              <div class="advantages-card__title">Services</div>
              <div class="advantages-card__text">
                Send letters, photos, gifts, make video calls or use online chat
              </div>
            </div>
          </div>
          <div class="advantages-card">
            <div class="advantages-card__inner">
              <div class="advantages-card-img">
                <div class="advantages-card-img__inner">
                  <img src="public\img\quote-right.svg" alt="quote-right" />
                </div>
              </div>
              <div class="advantages-card__title">Verification</div>
              <div class="advantages-card__text">
                All profiles are checked by our risk department
              </div>
            </div>
          </div>
          <div class="advantages-card">
            <div class="advantages-card__inner">
              <div class="advantages-card-img">
                <div class="advantages-card-img__inner">
                  <img src="public\img\quote-right.svg" alt="quote-right" />
                </div>
              </div>
              <div class="advantages-card__title">Protection</div>
              <div class="advantages-card__text">
                Your private data is strongly encrypted and protected - your
                safety is guaranteed
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </b-container>
</template>

<script>
export default {
  name: "Advantage",
  components: {},
  data() {
    return {};
  },
};
</script>

<style >
.advantages {
  background-color: #f5f6f8;
  height: 555px;
}
.advantages {
  background: #f5f6f8;
}
.advantages__inner {
  padding: 80px 0;
}
.advantages__title {
  text-align: center;
  margin-bottom: 90px;
}
.advantages__items {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-column-gap: 30px;
  grid-row-gap: 15px;
}
.advantages-card {
  background: #ffffff;
  border-radius: 15px;
}
.advantages-card__inner {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 0 20px 20px 20px;
}
.advantages-card__title {
  font-family: "Open-Sans-Bold", sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 25px;
  /* identical to box height */
  padding-bottom: 10px;
  /* Gray 1 */
  color: #333333;
}
.advantages-card__text {
  font-family: "Open-Sans-400", sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 24px;
  /* or 150% */
  text-align: center;
  /* Gray 3 */
  color: #828282;
  text-align: center;
}
.advantages-card-img {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100px;
  width: 100px;
  border-radius: 50%;
  background: linear-gradient(91.36deg, #f1717e -3.75%, #f59e86 99.33%);
  margin-top: -50px;
}
.advantages-card-img__inner {
  height: 80px;
  width: 80px;
  border-radius: 50%;
  border: 1px solid #fff;
}

</style>
