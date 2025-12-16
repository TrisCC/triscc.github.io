<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';
	import '../app.css';

	let { children } = $props();

	export const prerender = true;
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<div class="flex flex-col min-h-screen font-sans text-gray-800">
	<header class="bg-gray-100 p-4 border-b border-gray-300">
		<nav class="flex justify-center gap-4">
			<a href="/" class="text-gray-800 font-medium hover:text-blue-600">Home</a>
			<a href="#projects" class="text-gray-800 font-medium hover:text-blue-600">Projects</a>
			<a href="#contact" class="text-gray-800 font-medium hover:text-blue-600">Contact</a>
		</nav>
	</header>

	<main class="flex-1 p-8">
		{@render children()}
	</main>

	<footer class="bg-gray-100 p-4 text-center border-t border-gray-300">
		<p>&copy; 2025 Tristan. All rights reserved.</p>
	</footer>
</div>
