<template>
	<div>
		<h1 class="text-700">
			{{ msg }}
		</h1>
		<h2 class="text-400">Prime Vue Tutorial</h2>
	</div>

	<div class="card flex flex-column gap-2 w-5 justify-content-center">
		<Button label="Check" icon="pi pi-check" />
		<Calendar v-model="date" />
		<span class="inline">{{ date }}</span>
		<div class="card flex justify-content-center">
			<ToggleButton
				v-model="checked"
				class="w-6rem"
				onLabel="On"
				offLabel="Off"
			/>
		</div>
		<div class="card flex flex-column gap-2 justify-content-center">
			<FloatLabel>
				<InputText id="username" v-model="username" />
				<label for="username">Username</label>
			</FloatLabel>
			<span class="inline-block text-600 ml-2">{{ username }}</span>
		</div>
	</div>
</template>

<script>
export default {
	data() {
		return {
			msg: 'Welcome to Your Vue.js App',
			date: null,
			checked: false,
			username: '',
		};
	},
};
</script>
