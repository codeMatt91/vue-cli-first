<template>
  <div class="container">
    <Title />
    <Jumbotron />
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Jumbotron from "./components/Jumbotron.vue";

export default {
  name: "App",
  components: {
    Title,
    Jumbotron,
  },
};
</script>

<style>
.container{
  background-color: cadetblue;
}
</style>
