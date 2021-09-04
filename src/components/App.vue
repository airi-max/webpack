<template>
  <div>
    <h1>
      <router-link to="/order/cart">あ</router-link>
    </h1>
    <p>pp</p>
    <Header></Header>
    <Body></Body>
  </div>
</template>

<script>
import Header from "./Header.vue"
import Body from "./Body.vue"
import js from "../index.js";

export default: {
  mixins: [js],
  components: {
    Header,
    Body,
  },
}
</script>

<style>

</style>