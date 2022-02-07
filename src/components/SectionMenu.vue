<template>
  <div class="SectionMenu">
    <h2>Come mi sento oggi?</h2>
    <div>
      <ul class="">
        <li>Super Abbacchio</li>
        <i class="fas fa-smile-wink"></i>
        <li>Mezz'Abbacchio <i class="fas fa-meh-rolling-eyes"></i></li>
        <li>Abbacchiato <i class="fas fa-sad-cry"></i></li>
        <li class="h4">Abbacchio Scottadito</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionMenu",
};
</script>

<style>
.SectionMenu {
  text-align: center;
  padding: 10px;
}
h2 {
  margin-top: 10px;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  padding: 5px;
}
</style>
