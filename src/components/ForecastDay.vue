<template>
	<div class="hello">
		<h2>{{ day }}</h2>
	</div>
</template>

<script>
export default {
	name: 'ForecastDay',
	props: {
		day: String
	}
};
</script>
<style></style>
