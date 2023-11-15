<script lang="ts"></script>

<div id="coin">
	<button>+</button>
	<div id="info">
		<div id="value">Value:</div>
		<div id="amount">Amount:</div>
	</div>
	<button>-</button>
</div>

<style>
	#coin {
		background: var(--secondary-dark);
		border-radius: var(--border-radius);
		width: 80px;
		height: 120px;
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: column;
		width: min-content;
		height: min-content;
		box-sizing: border-box;
		padding: var(--padding-small);
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
		width: 1rem;
		height: 1rem;
		display: flex;
		align-content: center;
		justify-content: center;
		cursor: pointer;
	}
</style>
