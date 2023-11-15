<script lang="ts">
	import Player from "./Player.svelte";
	import Coin from "./Coin.svelte";
</script>

<div id="game">
	<div class="title">Bank</div>
	<div id="bank">
		<div id="balance">Total Balance:</div>
		<div>Coins:</div>
		<div id="coins">
			<Coin />
			<Coin />
			<Coin />
			<Coin />
			<Coin />
			<Coin />
			<Coin />
			<Coin />
			<Coin />
			<Coin />
			<Coin />
			<button id="add-coin">+</button>
		</div>
	</div>

	<div class="title">Players</div>
	<div id="players">
		<Player />
	</div>
</div>

<style>
	.title {
		font-size: 1.5rem;
		margin-bottom: var(--padding-small);
	}

	#players,
	#bank {
		width: 100%;
	}

	#coins {
		width: 100%;
		display: flex;
		flex-wrap: wrap;
	}

	#add-coin {
		width: var(--coin-width);
		height: var(--coin-height);
		border: none;
		background-color: var(--secondary-dark);
		border-radius: var(--border-radius);
	}
</style>
