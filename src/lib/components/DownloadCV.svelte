<script lang="ts">
	import Slide from "./Slide.svelte";
</script>

<Slide animate>
	<Slide animate>
		If you like more <span data-auto-animate-id="word" class="traditional">traditional</span>
		CV format you can
		<a href="https://dox.abv.bg/download?id=df773582d5" target="_blank">⬇️</a>
		it.
	</Slide>

	<Slide animate>
		If you like more <span data-auto-animate-id="word" class="boring">boring</span> CV format
		you can
		<a href="https://dox.abv.bg/download?id=df773582d5" target="_blank">⬇️</a>
		it.
	</Slide>
</Slide>

<style>
	.traditional {
		color: greenyellow;
	}

	.boring {
		color: orangered;
	}
</style>
