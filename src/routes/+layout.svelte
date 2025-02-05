<script>
	// Import the global CSS file for styling
	import '../app.css'; 
	
	// Retrieve the passed props, specifically "children" (content of the layout)
	let { children } = $props();
</script>

<header>
	<h1>Header</h1> <!-- The header section of the page -->
</header>

<main>
	{@render children()} <!-- This is where the dynamic content is inserted -->
</main>

<footer>
	<h1>Footer</h1> <!-- The footer section of the page -->
</footer>
