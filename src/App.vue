<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
html,
body,
#app {
  width: 100%;
  height: 100%;
  margin: 0 auto;
}

@media (min-width: 1024px) {
  #app {
    width: 1024px;
  }
}
</style>
