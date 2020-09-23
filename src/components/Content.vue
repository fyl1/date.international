<template>
  <b-container class="content">
    <Search />

    <b-card-group deck>
      <Card />
      <Card />
      <Card />
    </b-card-group>

    <b-card-group deck>
      <Card />
      <Card />
      <Card />
    </b-card-group>

    <b-card-group deck>
      <Card />
      <Card />
      <Card />
    </b-card-group>
    <b-container>
      <b-row class="text-center" align-v="center">
        <b-col></b-col>
        <b-col
          ><b-button class="more-button" variant="light"
            >show more</b-button
          ></b-col
        >
        <b-col></b-col>
      </b-row>
    </b-container>
  </b-container>
</template>

<script>
import Search from "../components/Search";
import Card from "../components/Card";

export default {
  name: "Content",
  components: { Search, Card },
};
</script>

<style>
.content {
  background: linear-gradient(180deg, #f1717e 0%, #f59e86 100%);
}
.card-deck {
  margin: 0 10px 10px 10px;
}
.more-button {
  margin-bottom: 15px;
}
</style>
