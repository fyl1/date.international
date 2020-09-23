<template>
  <b-container class="header">
    <b-row>
      <b-col class="float-left"
        ><router-link to="/" class="logo">
          <h1>DATE.<span>INTERNATIONAL</span></h1>
        </router-link></b-col
      >
      <b-col><Registration /></b-col>
    </b-row>
  </b-container>
</template>

<script>
import Registration from "../components/Registration";
export default {
  name: "Header",
  components: {
    Registration,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  background-color: #fff;
}
.logo {
  text-decoration: none;
  color: #f48c7f;
  font-style: normal;
  font-weight: 800;
  font-size: 18px;
  line-height: 25px;
  letter-spacing: 0.02em;
  text-transform: uppercase;
}
.logo span {
  color: #000;
}
</style>
