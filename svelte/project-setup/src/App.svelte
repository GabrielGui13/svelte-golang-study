<script>
	export let name;
	let age = 20;

	const incrementAge = () => {
		age += 1
	}
</script>

<style>
	h1 {
		color: red;
	}
</style>

<h1>Hello {name}, my age is {age}!</h1>
<button on:click={incrementAge}>Change age!</button>
