<template>
  <header>
    <div class="navBar">
      헤더
    </div>
  </header>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
  background: yellow;
  padding-left: 100px;
  padding-right: 100px;
}
.navBar {
  background: blue;
}
@media (max-width: 1024px) {
  header {
    padding: 0;
  }
}
</style>
