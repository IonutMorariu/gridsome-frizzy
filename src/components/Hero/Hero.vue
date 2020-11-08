<template>
	<div class="hero-container py-10 flex justify-center items-center flex-col">
		<h1 class="text-4xl font-bold text-white">Frizzy Board</h1>
		<h2 class="text-xl font-semibold text-white">Arduino Compatible board</h2>
		<button
			class="px-4 py-2 my-4 border border-solid border-purple-100 font-semibold text-purple-100 rounded-lg hover:bg-purple-100 hover:bg-opacity-25"
		>
			Learn more
		</button>
	</div>
</template>

<script>
export default {
	name: 'Hero',
}
</script>

<style>
.hero-container {
	background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.5)),
		url('./hero-background.png');
	background-position: center center;
	background-size: cover;
}
</style>
