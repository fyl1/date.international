<template>
  <div class="home-page">
    <section class="talk">
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
    </section>
  </div>
</template>

<script>
import { mapGetters } from "vuex";
import RwvTag from "@/components/VTag";
import { FETCH_TAGS } from "@/store/actions.type";

export default {
  name: "home",
  components: {
    RwvTag
  },
  mounted() {
    this.$store.dispatch(FETCH_TAGS);
  },
  computed: {
    ...mapGetters(["isAuthenticated", "tags"]),
    tag() {
      return this.$route.params.tag;
    }
  }
};
</script>
