<script lang="ts">
	import Slide from "./slide.svelte";
</script>

<Slide animate>
	<p>Auto-animate</p>
</Slide>

<Slide animate>
	<p class="red">Auto-animate</p>
</Slide>

<Slide animate>
	<Slide>Vertical slide 1</Slide>
	<Slide>Vertical slide 2</Slide>
</Slide>

<style>
	.red {
		margin-top: 100px;
		color: rebeccapurple;
	}
</style>