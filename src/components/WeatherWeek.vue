<template>
  <div>
    <WeatherDay message="monday"/>
    <WeatherDay message="tuesday"/>
    <WeatherDay message="wednesday"/>
    <WeatherDay message="thursday"/>
    <WeatherDay message="friday"/>
    <WeatherDay message="saturday"/>
    <WeatherDay message="sunday"/>
  </div>
</template>

<script>
import WeatherDay from "./WeatherDay.vue";

export default {
  components: {
    WeatherDay
  }
};
</script>

<style lang="scss" scoped>
div {
  flex: 1;
  display: flex;
}
</style>
