<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Header />
    <Content />
    <Advantage />
    <Feed />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Content from "@/components/Content.vue";
import Advantage from "@/components/Advantage.vue";
import Feed from "@/components/Feed.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Content,
    Advantage,
    Feed,
    Footer,
  },
};
</script>
<style scoped></style>
