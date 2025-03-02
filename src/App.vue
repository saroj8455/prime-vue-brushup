<template>
	<h1>Prime Vue Tutorial</h1>
	<div class="card flex flex-column gap-2 w-5 justify-content-center">
		<Button label="Check" icon="pi pi-check" />
		<Calendar v-model="date" />
	</div>
	<!-- <HelloWorld msg="Vite + Vue" /> -->
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
export default {
	data() {
		return {
			date: null,
		};
	},
};
</script>
