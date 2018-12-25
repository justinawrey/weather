<template>
  <div id="app">
    <WeatherWeek message="hello"/>
    <WeatherWeek message="hello"/>
  </div>
</template>

<script>
import WeatherWeek from "./components/WeatherWeek.vue";

export default {
  components: {
    WeatherWeek
  }
};
</script>

<style lang="scss">
body,
html {
  width: 100%;
  height: 100%;
}

body {
  display: flex;
}

#app {
  flex: 1;
  display: flex;
  flex-direction: column;
}
</style>
