<template>
	<Layout>
		<!-- Learn how to use images here: https://gridsome.org/docs/images -->
		<Hero />

		<Description
			content="We are a group of Open-Source Electronics enthusiasts. We design and develop projects for a multitude of
			applications, from IOT to education, focusing on usability and functionality."
			header="About Frizzy"
		/>

		<p class="mb-4">
			<a
				class="mr-4 text-teal-600 hover:underline"
				href="https://gridsome.org/docs"
				target="_blank"
				rel="noopener"
				>Gridsome Docs</a
			>
			<a
				class="mr-4 text-teal-600 hover:underline"
				href="https://github.com/gridsome/gridsome"
				target="_blank"
				rel="noopener"
				>GitHub</a
			>
		</p>
	</Layout>
</template>

<script>
import Hero from '~/components/Hero/Hero.vue'
import Description from '~/components/Description/Description.vue'

export default {
	components: {
		Hero,
		Description,
	},
	metaInfo: {
		title: 'Inicio',
	},
}
</script>
