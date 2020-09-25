<template>
  <b-container class="footer">
    <div class="container">
      <div class="footer__inner">
        <router-link class="logo-font" :to="{ name: 'home', params: {} }">
          <div class="footer__logo">
            <div class="logo-img">
              <div class="logo__inner">
                <img src="img/date.international.svg" alt="logo" />
              </div>
            </div>
          </div>
        </router-link>
        <div class="footer-copy">
          <div class="footer-copy__inner">
            <a
              class="footer-copy__link"
              rel="noopener noreferrer"
              target="blank"
              href="https://thinkster.io"
              >Copyright © Date.International. All rights reserved.</a
            >
          </div>
        </div>
      </div>
      <div class="footer-to-top">
        <div class="to-top">
          <div class="to-top__inner">
            <div class="to-top__icon">
              <span></span>
            </div>
          </div>
        </div>
      </div></div
  ></b-container>
</template>

<script>
export default {
  name: "footer",
  components: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
  background-color: #fff;
  height: 91px;
}
.footer__inner {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.footer__logo {
  width: 100%;
  max-width: 187px;
  height: 22px;
}
.footer-copy__link {
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 19px;
  text-align: center;
  color: #bdbdbd;
}
.footer-to-top {
  position: absolute;
  top: -20px;
  right: 10%;
  width: 48px;
  height: 48px;
}
.to-top {
  width: 48px;
  height: 48px;
  border-radius: 50%;
  background-color: #f48c7f;
  box-shadow: inset 0px 1px 0px rgba(255, 255, 255, 0.25);
}
.to-top__inner {
  height: 100%;
  width: 100%;
}
.to-top__icon {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 100%;
}
.to-top__icon > span {
  display: block;
  width: 12px;
  height: 12px;
  border-bottom: 4px solid #fff;
  border-right: 4px solid #fff;
  transform: rotate(-135deg);
  margin-top: 4px;
}
</style>
