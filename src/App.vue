<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <CompView />
  <h4>SASS</h4>
</template>

<script>
import CompView from "@/components/CompView.vue";

export default {
  name: "App",
  components: {
    CompView,
  },
};
</script>

<style lang='scss' scoped>
@import "@/assets/_shared.scss";

h4 {
  color: $blue;
}
</style>
