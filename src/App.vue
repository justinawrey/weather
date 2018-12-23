<template>
  <div id="app">
    <WeatherPanel message="hello"/>
    <WeatherPanel message="hello"/>
  </div>
</template>

<script>
import WeatherPanel from "./components/WeatherPanel.vue";

export default {
    components: {
        WeatherPanel
    }
};
</script>

<style lang="scss">
#app {
    color: yellow;
}
</style>
