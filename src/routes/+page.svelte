<script>
	// Declare a reactive variable to store the input message
	let message = $state('Hello!'); // Ensure $state is correctly defined in your framework
</script>

<!-- Heading for the input section -->
<h1>Write down something please:</h1>

<!-- Display the current value of the message variable -->
<h3>{message}</h3>

<!-- Input field bound to the message variable -->
<input type="text" bind:value={message} />

<style>
	/* Global styles for the body */
	:global(body) {
		font-family: Arial, sans-serif; 
		background-color: #f4f4f4; 
		color: #333;
		display: flex; /* Use flexbox for layout */
		flex-direction: column; 
		justify-content: space-between; 
		height: 100vh; /* Full viewport height */
	}

	/* Styling for the input field */
	input {
		padding: 0.5rem; 
		font-size: 1rem; 
		border: 1px solid #ccc; 
		border-radius: 4px; 
		width: 100%; /* Make input take full width */
		max-width: 300px; 
		margin-top: 1rem; 
		outline: none; 
	}
</style>
