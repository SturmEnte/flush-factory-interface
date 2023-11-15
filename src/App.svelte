<script lang="ts">
	import Game from "./lib/Game.svelte";
</script>

<div id="wrapper">
	<main><Game /></main>

	<footer>
		<a href="https://www.flaticon.com/free-icons/playing-cards" title="playing cards icons" target="_blank">Playing cards icons created by Freepik - Flaticon</a>
		<span>●</span>
		<a href="https://github.com/SturmEnte/flush-factory-interface" target="_blank">Source Code</a>
	</footer>
</div>

<style>
	#wrapper {
		display: flex;
		flex-direction: column;
		/* width: calc(100vw - var(--scrollbar-width)); */
		width: 100vw;
		height: 100vh;
		overflow-x: hidden;
		overflow-y: auto;
	}

	main {
		width: 100%;
		min-height: calc(100vh - var(--footer-height));
		padding: var(--padding);
	}

	main,
	footer {
		box-sizing: border-box;
	}

	footer {
		padding: 0 var(--padding);
		width: 100%;
		height: var(--footer-height);
		font-size: 0.6rem;
		background: var(--secondary-dark);
		display: flex;
		align-items: center;
		justify-content: center;
	}

	footer a {
		font-weight: bold;
		text-decoration: none;
	}

	footer a,
	footer span {
		color: var(--primary-dark);
	}

	footer span {
		margin: 0 5px;
	}
</style>
