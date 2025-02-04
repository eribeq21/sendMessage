<script>
	let message = $state('Hello!');
</script>

<h1>Write down something please:</h1>
<h3>{message}</h3>
<input type="text" bind:value={message} />

<style>
	:global(body) {
		font-family: Arial, sans-serif;
		background-color: #f4f4f4;
		color: #333;
		display: flex;
		flex-direction: column;
		justify-content: space-between;
		height: 100vh;
	}
	input {
		padding: 0.5rem;
		font-size: 1rem;
		border: 1px solid #ccc;
		border-radius: 4px;
		width: 100%;
		max-width: 300px;
		margin-top: 1rem;
		outline: none;
	}
</style>
