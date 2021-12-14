<template>
  <div class="m-0">
    <Header />
    <div id="nav"></div>
    <router-view />
  </div>
</template>
<script>
import Header from "./components/navigation/Header.vue";

export default {
  components: {
    Header,
  },
};
</script>

<style></style>
