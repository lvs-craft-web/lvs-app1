<template>
	<img alt="Vue logo" src="./assets/logo.png" />
	<HelloWorld msg="Welcome from Slava" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
	name: 'App',
	components: {
		HelloWorld,
	},
}
</script>

<style>
#app {
	@import url('https://fonts.googleapis.com/css2?family=Victor+Mono:wght@400;700&display=swap');
	background: #455a64 0 0 repeat;
	color: #3c6;
	font: 1.25rem 'Victor Mono', monospace;
	padding: 0 1.25rem 6.25rem;
}
</style>
