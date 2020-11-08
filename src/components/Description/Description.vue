<template>
	<div class="px-4 py-4">
		<h1 class="text-center font-semibold text-2xl">{{ header }}</h1>
		<p>
			{{ content }}
		</p>
	</div>
</template>

<script>
export default {
	name: 'Description',
	props: {
		header: {
			type: String,
			required: true,
		},
		content: {
			type: String,
			required: true,
		},
	},
}
</script>

<style></style>
