<template>
  <div class="container">
    <Title />
    <Jumbotron />
    <SectionMenu />
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Jumbotron from "./components/Jumbotron.vue";
import SectionMenu from "./components/SectionMenu.vue";
export default {
  name: "App",
  components: {
    Title,
    Jumbotron,
    SectionMenu,
  },
};
</script>

<style>
.container {
  background-color: cadetblue;
}
</style>
