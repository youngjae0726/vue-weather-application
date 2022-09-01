<template>
  <div>
    <HederDisplay />
    <hr />
    <WeatherContent />
  </div>
</template>

<script>
import HederDisplay from "./components/HeaderDisplay";
import WeatherContent from "./components/weather/WeatherContent";

export default {
  name: "App",
  components: {
    HederDisplay,
    WeatherContent,
  },
};
</script>

<style></style>
