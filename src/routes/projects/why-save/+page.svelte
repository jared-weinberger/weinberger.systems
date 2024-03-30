<script>
	let startingAmount = 0
	let contribution = 0
	let frequency = 'monthly'
	function showValues() {
		alert(`${startingAmount}, ${contribution}, ${frequency}`)
	}
	export { startingAmount, contribution, frequency, showValues }
</script>

<main class="container p-2">
	<form on:submit|preventDefault|stopPropagation={showValues}>
		<input type="number" bind:value={startingAmount} />
		<input type="number" bind:value={contribution} />
		<input type="text" bind:value={frequency} />
		<button type="submit">Calculate</button>
	</form>
</main>
