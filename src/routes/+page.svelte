<script>
	// Declare a reactive variable to store the input message
	let message = $state('Hello!'); // Ensure $state is correctly defined in your framework
</script>

<!-- Container for layout -->
<div class="container">
	<!-- Heading for the input section -->
	<h1>Write something:</h1>

	<!-- Display the current value of the message variable -->
	<p class="message">{message}</p>

	<!-- Input field bound to the message variable -->
	<input type="text" bind:value={message} placeholder="Type here..." />
</div>

<style>
	/* General styles */
	.container {
		font-family: Arial, sans-serif;
		background-color: #e0f7fa;
		color: #01579b;
		text-align: center;
		padding: 2rem;
		border-radius: 10px;
		box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
		width: 90%;
		max-width: 400px;
		margin: auto;
		margin-top: 10%;
	}

	/* Styling for the displayed message */
	.message {
		font-size: 1.5rem;
		font-weight: bold;
		margin: 1rem 0;
	}

	/* Styling for the input field */
	input {
		padding: 0.6rem;
		font-size: 1rem;
		border: 2px solid #0288d1;
		border-radius: 6px;
		width: 100%;
		outline: none;
	}
</style>