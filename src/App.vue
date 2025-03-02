<template>
	<!-- <HelloWorld msg="Vite + Vue" /> -->
	<Welcome />
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue';
import Welcome from '@/components/Welcome.vue';
export default {
	data() {
		return {
			date: null,
			checked: false,
			username: '',
		};
	},
	method: {},
};
</script>
