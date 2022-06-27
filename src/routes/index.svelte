<script context="module">
	export const prerender = true;
</script>

<script>
	import Contact from '$lib/Contact/Contact.svelte';
	import Gallery from '$lib/gallery/Gallery.svelte';
	import Header from '$lib/header/Header.svelte';
	import Leader from '$lib/leader/Leader.svelte';
	import Project from '$lib/project/Project.svelte';
	import Provide from '$lib/provide/Provide.svelte';
	import Services from '$lib/services/Services..svelte';
	import Skills from '$lib/skills/Skills.svelte';
	import { text } from 'svelte/internal';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
	<link
		href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
		rel="stylesheet"
		integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
		crossorigin="anonymous"
	/>
	<style>
		@import '@fontsource/inter';
		@import url('../assets/fonts/fonts.css');
		:root {
			--font-i: 'Inter', sans-serif;
			--font-m: 'Melish', sans-serif;
			--white: #fff;
			--yellow: #ffb342;
			--blue: #1c2752;
			--lightBlue: rgba(28, 39, 82, 0.86);
			--dark: #222222;
			--grey: #7e7e7e;
			--light: #f2f2f2;
			--grey2: #d2d2d2;
			--shadow: rgba(255, 255, 255, 0.2);
		}
		* {
			margin: 0;
			padding: 0;
			box-sizing: border-box;
			text-decoration: none;
			list-style-type: none;
			border: none;
			border-radius: none;
			outline: none;
			scroll-behavior: smooth;
		}
		body {
			margin: 0;
			background: var(--light);
			font-family: var(--font-i);
		}
		.container {
			max-width: 1320px;
			width: 100%;
			margin: 0 auto;
			padding: 0 12px;
		}

		h1,
		h2,
		h3,
		h4,
		h5,
		h6,
		span {
			font-family: var(--font-m);
			margin-bottom: 0;
		}
		p {
			margin-bottom: 0;
		}
		ul {
			padding-left: 0;
			margin-bottom: 0;
		}
		a {
			text-decoration: none;
		}
	</style>
</svelte:head>

<Header />
<Leader />
<Provide />
<Services />
<Skills />
<Project />
<Gallery />
<Contact />
