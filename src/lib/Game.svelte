<script lang="ts">
	import Player from "./Player.svelte";
	import Coin from "./Coin.svelte";
</script>

<div id="game">
	<div class="title">Bank</div>
	<div id="bank">Total Balance:</div>
	<div id="coins">
		<Coin />
		<button>Add Coins</button>
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
</style>
