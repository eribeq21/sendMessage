<script>
	import '../app.css';
	let { children } = $props();
</script>

<header>
	<h1>Header</h1>
</header>

<main>
	{@render children()}
</main>

<footer>
	<h1>Footer</h1>
</footer>
