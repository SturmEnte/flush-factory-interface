<script lang="ts">
</script>

<div id="coin">
	<button id="plus">+</button>
	<div id="info">
		<div id="value">Value:</div>
		<div id="amount">Amount:</div>
	</div>
	<button id="minus">-</button>
</div>

<style>
	#coin {
		background: var(--secondary-dark);
		border-radius: var(--border-radius);
		min-width: var(--coin-width);
		height: var(--coin-height);
		min-height: var(--coin-height);
		max-height: var(--coin-height);
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: column;
		/* width: min-content;
		height: min-content; */
		/* box-sizing: border-box;
		padding: var(--padding-small); */
		margin: 0 var(--padding-small) var(--padding-small) 0;
	}

	#info {
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: column;
		margin: var(--padding-small) 0;
	}

	#value {
		/* margin: var(--padding-small) 0; */
	}

	button {
		border: none;
		background: var(--accent);
		border-radius: 360px;
		width: 1.2rem;
		height: 1.2rem;
		padding: 0;
		/* display: flex;
		align-content: center;
		justify-content: center; */
		cursor: pointer;
		text-align: center;
		vertical-align: middle;
	}

	#plus {
		background: var(--green);
	}

	#minus {
		background: var(--red);
	}
</style>
