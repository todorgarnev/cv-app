<script lang="ts">
	import Slide from "./Slide.svelte";
</script>

<Slide animate>
	<p>You can 🤙 me ➡️ 0896 117 335</p>
	<p>or 📬 me ➡️ todorgarnev@gmail.com</p>

	<div>
		<a href="https://www.linkedin.com/in/%F0%9F%92%BB-todor-garnev-2880425a/" target="_blank">
			<i class="devicon-linkedin-plain" />
		</a>

		<a href="https://github.com/todorgarnev" target="_blank">
			<i class="devicon-github-original" />
		</a>
	</div>
</Slide>

<style>
	div {
		margin-top: 5rem;
	}

	a {
		--r-link-color: #fff;
		--r-link-color-hover: #fff;

		&:first-child {
			margin-right: 5rem;
		}
	}
</style>
