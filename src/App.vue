<template>
  <div class="app">
  <navigation/>
</div>
<router-view/>
</template>
<script>
import Navigation from "./components/Navigation.vue"
export default {
  name:"App",
  components: {
    Navigation
  },
};
</script>

<style lang="scss" >
@import url("https://fonts.googleapis.com/css2?family=raleway:wght@400;500&display=swap");
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: "Raleway",sans-serif;
  font-weight: 400;
}
.app {
  min-height: 100vh;
  position: relative;
  background-color: #fff;
}
.continer{
  padding: 0 20px;
  max-width: 1140px;
  margin: 0 auto;
}
</style>