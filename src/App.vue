<template>
	<img alt="Vue logo" src="./assets/logo.png" />
	<HelloWorld msg="Vue Weather App" />
  <ForecastDay day="Monday" />
  <ForecastDay day="Tuesday" />
  <ForecastDay day="Wednesday" />
  <ForecastDay day="Thursday" />
  <ForecastDay day="Friday" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import ForecastDay from './components/ForecastDay.vue';

export default {
	name: 'App',
	components: {
		HelloWorld,
    ForecastDay
	}
};
</script>

<style></style>
