<template>
  <div>
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

<style></style>
