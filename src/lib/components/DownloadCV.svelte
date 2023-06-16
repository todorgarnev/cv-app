<script lang="ts">
	import Slide from "./Slide.svelte";
</script>

<Slide animate>
	<Slide animate bg="linear-gradient(to bottom, #283b95, #17b2c3)">
		If you like more <span class="traditional">traditional</span>
		CV format you can
		<a href="https://dox.abv.bg/download?id=df773582d5" target="_blank">⬇️</a>
		it.
	</Slide>

	<Slide animate bg="radial-gradient(#283b95, #17b2c3)">
		If you like more <span class="boring">boring</span> CV format you can
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
