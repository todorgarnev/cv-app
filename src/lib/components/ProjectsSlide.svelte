<script lang="ts">
	import Slide from "./Slide.svelte";
</script>

<Slide>
	<Slide animate bgGradient="linear-gradient(to top, #101010, #585858)">
		<h3>Personal projects</h3>
	</Slide>

	<Slide animate bgGradient="linear-gradient(to bottom, #101010, #585858)">
		<h3>Personal projects</h3>

		<div>
			<a href="https://curious-narwhal-dcc41a.netlify.app/" target="_blank"
				>Rock, Paper, Scissors, Lizard, Spock game</a
			>
			-
			<i class="devicon-svelte-plain" title="SvelteKit" />
		</div>

		<div>
			<a href="https://target-sum.netlify.app/" target="_blank">Target sum</a>
			-
			<i class="devicon-svelte-plain" title="SvelteKit" />
		</div>

		<div>
			<a href="https://fervent-feynman-6714ff.netlify.app/" target="_blank">Mini games</a>
			-
			<i class="devicon-react-original" title="React" />
		</div>

		<div>
			<a href="https://heuristic-hawking-e894c6.netlify.app/" target="_blank">Memory cards</a>
			-
			<i class="devicon-react-original" title="React" />
		</div>

		<div>
			<a href="https://eager-kalam-42bf68.netlify.app/" target="_blank">Classic snake game</a>
			-
			<i class="devicon-react-original" title="React" />
		</div>
	</Slide>
</Slide>

<style>
	div {
		font-size: 2.5rem;
	}

	a {
		text-decoration: underline !important;
	}

	i {
		color: dodgerblue;
	}
</style>