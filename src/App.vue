<template>
  <div id="app">
      <Talks></Talks>
  </div>
</template>

<script>
import Talks from "./components/Talks";

export default {
  name: "app",
  components: {
    Talks
  }
};
</script>

<style lang="scss">
#app {
  margin-top: 20px;
}
</style>
