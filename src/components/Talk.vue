<template>
  <b-container class="talk">
    <div class="container">
      <div class="talk__inner">
        <h2 class="talk__title">
          Talk to the most beautiful ladies from
          <span class="text-red">Ukraine, Russia and Belarus</span>
        </h2>
        <div class="talk-btn-wrapp">
          <button class="btn btn-create-account">
            <div class="btn__body-wrapp">
              <div class="btn__body">
                <span class="btn__text">CREATE AN ACCOUNT</span>
              </div>
            </div>
          </button>
        </div>
      </div>
    </div>
  </b-container>
</template>

<script>
import Registration from "../components/Talk";
export default {
  name: "Talk",
  components: {
    Talk,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.talk {
  background-image: url("../../public/img/talk-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
.talk__inner {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 87px 0;
}
.talk__title {
  max-width: 770px;
  padding-bottom: 36px;
  color: #fff;
}
</style>
