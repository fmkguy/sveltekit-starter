<script>
	import Button from '$lib/components/Button.svelte';
	let count = 0;
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<p>
	Count: <strong>{count}</strong>
	<Button on:click={() => count++}>Increment Counter</Button>
</p>
