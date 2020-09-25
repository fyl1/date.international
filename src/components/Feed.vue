<template>
  <b-container class="feed">
    <div class="container">
      <div class="testimonial__inner">
        <h2 class="testimonial__title">
          Testimonials
          <span class="text-red">&ensp;Couple</span>
        </h2>
        <div class="testimonial__items">
          <div class="testimonial-card">
            <div class="testimonial-card__inner">
              <div class="testimonial-card__title">
                Natalia and Sean!
                <div class="testimonial-card__title-img">
                  <img src="public\img\quote-right.svg" alt="quote-right" />
                </div>
              </div>
              <div class="testimonial-card__text">
                You know, Natalia and I have been chatting since February and
                both felt a special spark right from the first day. After
                millions of letters and thousands of telephone calls we decided
                to date each other in Ukraine. Actually, I was a little bit
                nervous ...
              </div>
              <div class="testimonial-card__more">Read more</div>
            </div>
          </div>
          <div class="testimonial-card">
            <div class="testimonial-card__inner">
              <div class="testimonial-card__title">
                Michael and Mariya
                <div class="testimonial-card__title-img">
                  <img src="public\img\quote-right.svg" alt="quote-right" />
                </div>
              </div>
              <div class="testimonial-card__text">
                Hi, everyone! I want to tell you my amazing story about magic
                love and tender feelings. I have been searching for an ideal
                wife and best friend all of my life and now my search is over! I
                finally discovered the most incredible girl I have ever known.
                ...
              </div>
              <div class="testimonial-card__more">Read more</div>
            </div>
          </div>
          <div class="testimonial-card">
            <div class="testimonial-card__inner">
              <div class="testimonial-card__title">
                Richard and Olga
                <div class="testimonial-card__title-img">
                  <img src="public\img\quote-right.svg" alt="quote-right" />
                </div>
              </div>
              <div class="testimonial-card__text">
                Summer is the best time to fall in love, I think. And it
                happened to me too in June. I met my Richard one summer evening
                when I didn’t suppose something special could happen to me. That
                is why, ladies, I can’t stop saying : “Nobody could know what
                goo...
              </div>
              <div class="testimonial-card__more">Read more</div>
            </div>
          </div>
        </div>
        <div class="testimonial-btn-wrapp">
          <button class="btn btn-show-more">
            <div class="btn__body-wrapp">
              <div class="btn__body">
                <span class="btn__text">CREATE AN ACCOUNT</span>
              </div>
            </div>
          </button>
        </div>
      </div>
    </div></b-container
  >
</template>

<script>
export default {
  name: "Feed",
  components: {},
  data() {
    return {};
  },
};
</script>

<style>
.testimonial__inner {
  padding: 80px 0;
}
.testimonial__title {
  text-align: center;
  margin-bottom: 68px;
}
.testimonial__items {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-column-gap: 30px;
  grid-row-gap: 15px;
}
.testimonial-card__inner {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.testimonial-card__title {
  display: flex;
  justify-content: space-between;
  font-family: "Open-Sans-Bold", sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 25px;
  color: #333333;
}
.testimonial-card__text {
  font-family: "Open-Sans-400italic", sans-serif;
  font-size: 16px;
  line-height: 24px;
  color: #828282;
}
.testimonial-card__more {
  font-family: "Open-Sans-400italic", sans-serif;
  font-style: italic;
  font-weight: normal;
  font-size: 15px;
  line-height: 22px;
  /* identical to box height, or 147% */
  text-align: end;
  text-decoration-line: underline;
  /* Primary */
  color: #f48c7f;
}
.testimonial-btn-wrapp {
  display: flex;
  justify-content: center;
  margin-top: 50px;
}
</style>
