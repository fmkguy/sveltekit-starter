<button on:click>
	<slot />
</button>

<style lang="scss" scoped>
	button {
		background: tomato;
		border: 0;
		border-radius: 0.2rem;
		box-sizing: border-box;
		color: white;
		cursor: pointer;
		font: normal 600 1rem/2rem sans-serif;
		padding: 0.2rem 0.8rem;
	}
</style>
