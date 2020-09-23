<template>
  <b-card no-body class="overflow-hidden" style="max-width: 540px;">
    <b-row no-gutters class="text-center" align-v="center">
      <b-col>
        <b-card-img
          class="float-left m-2"
          thumbnail
          fluid
          src="https://i.pinimg.com/564x/c0/b7/7f/c0b77faeb2cb3e67fd1b423c4535f6c3.jpg"
          v-bind="imgProps"
        ></b-card-img>
      </b-col>
      <b-col>
        <b-card-body title="Name">
          <b-card-text>
            sity
          </b-card-text>
          <b-card-text>
            some text
          </b-card-text>
          <b-card-text>
            state
          </b-card-text>
        </b-card-body>
      </b-col>
    </b-row>
  </b-card>
</template>

<script>
export default {
  name: "Card",
  components: {},
  data() {
    return {
      imgProps: {
        width: 120,
        height: 170,
      },
    };
  },
};
</script>

<style>
.card-img {
  width: auto !important;
}
</style>
