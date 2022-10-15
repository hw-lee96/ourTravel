<script>
	import { push } from "svelte-spa-router";

	let count = 0;
	const increment = () => {
		count += 1;
	};
</script>

<button class="btn-big" on:click={increment}>
	count is {count}
</button>

<div>
	<button on:click={() => push("/")}> Go Main </button>
</div>


<style>
	.btn-big {
		width: 250px;
		height: 150px;
		margin-bottom: 100px;
	}
</style>