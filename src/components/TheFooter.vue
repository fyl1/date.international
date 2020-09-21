<template>
  <footer class="footer">
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
            >Copyright © Date.International. All rights reserved.</a>
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
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "RwvFooter"
};
</script>
