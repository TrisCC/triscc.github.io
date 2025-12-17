<script lang="ts">
	import favicon from '$lib/assets/favicon.ico';
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<div class="flex flex-col min-h-screen font-sans text-gray-800 dark:text-gray-200">
	<main class="flex-1">
		{@render children()}
	</main>

	<footer
		class="bg-gray-100 dark:bg-gray-800 p-4 text-center border-t border-gray-300 dark:border-gray-700"
	>
		<p class="text-gray-800 dark:text-gray-200">&copy; 2025 Tristan Cotino. All rights reserved.</p>
	</footer>
</div>
