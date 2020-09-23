<template>
  <b-row>
    <b-col
      ><b-dropdown text="age from" class="m-2" variant="light">
        <b-dropdown-item href="#">10</b-dropdown-item>
        <b-dropdown-item href="#">15</b-dropdown-item>
        <b-dropdown-item href="#">20</b-dropdown-item>
      </b-dropdown>
      <b-dropdown text="age to" class="m-2" variant="light">
        <b-dropdown-item href="#">90</b-dropdown-item>
        <b-dropdown-item href="#">85</b-dropdown-item>
        <b-dropdown-item href="#">80</b-dropdown-item>
      </b-dropdown>
    </b-col>
    <b-col><b-button class="m-2">Search now</b-button></b-col>
    <b-col
      ><b-button class="m-2 float-right" variant="light"
        >Advanced Search</b-button
      ></b-col
    >
  </b-row>
</template>

<script>
export default {
  name: "Search",
  components: {},
};
</script>

<style>
.btn-light,
.btn-secondary {
  border-radius: 25px !important;
  align-items: center;
  text-align: center;
  text-transform: uppercase;
  font-size: 14px;
  line-height: 19px;
}
</style>
