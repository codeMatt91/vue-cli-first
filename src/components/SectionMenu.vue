<template>
  <div class="SectionMenu">
    <h2>Come mi sento oggi?</h2>
    <div>
      <ul>
        <li>Super Abbacchio <i class="fas fa-smile-wink"></i></li>
        <li>Mezz'Abbacchio <i class="fas fa-meh-rolling-eyes"></i></li>
        <li>Abbacchiato <i class="fas fa-sad-cry"></i></li>
        <li>Scottadito <i class="fas fa-turkey"></i></li>
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
}
h2 {
  margin-top: 10px;
}
ul {
  list-style-type: none;
}
</style>
