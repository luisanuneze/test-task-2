<template>
  <div class="container">
    <div>
      <AppMain />
      <!-- <Videoproduktion /> -->
    </div>
  </div>
</template>

<script>
// import Videoproduktion from "../components/Videoproduktion.vue";
import AppMain from "../components/AppMain.vue";
export default {
  components: { AppMain }
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

html {
  background-color: #f8f9fa;
}
</style>
