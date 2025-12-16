<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';
	import '../app.css';

	let { children } = $props();

	export const prerender = true;
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<div class="container">
	<header>
		<nav>
			<a href="/">Home</a>
			<a href="#projects">Projects</a>
			<a href="#contact">Contact</a>
		</nav>
	</header>

	<main>
		{@render children()}
	</main>

	<footer>
		<p>&copy; 2025 Tristan. All rights reserved.</p>
	</footer>
</div>

<style>
	.container {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
		font-family:
			-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans',
			'Helvetica Neue', sans-serif;
		color: #333;
	}

	header {
		background: #f8f8f8;
		padding: 1rem;
		border-bottom: 1px solid #ddd;
	}

	nav {
		display: flex;
		justify-content: center;
		gap: 1rem;
	}

	nav a {
		text-decoration: none;
		color: #333;
		font-weight: 500;
	}

	main {
		flex: 1;
		padding: 2rem;
	}

	footer {
		background: #f8f8f8;
		padding: 1rem;
		text-align: center;
		border-top: 1px solid #ddd;
	}
</style>
