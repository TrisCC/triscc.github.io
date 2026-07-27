<script lang="ts">
	import favicon from '$lib/assets/favicon.ico';
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<div class="flex flex-col min-h-screen font-sans text-dim-grey-800 dark:text-dim-grey-200">
	<main class="flex-1">
		{@render children()}
	</main>

	<footer
		class="bg-taupe-50 dark:bg-gunmetal-900 p-4 text-center border-t border-dim-grey-300 dark:border-dim-grey-700"
	>
		<p class="text-dim-grey-800 dark:text-dim-grey-200">&copy; 2025 Tristan Cotino. All rights reserved.</p>
	</footer>
</div>
