<script lang="ts">
	import { onMount } from "svelte";
	import Reveal from "reveal.js";
	import Highlight from "reveal.js/plugin/highlight/highlight";

	import IntroductionSlide from "./IntroductionSlide.svelte";
	import ContactSlide from "./ContactSlide.svelte";
	import ExperienceSlide from "./ExperienceSlide.svelte";
	import EducationSlide from "./EducationSlide.svelte";
	import ProjectsSlide from "./ProjectsSlide.svelte";
	import DownloadCV from "./DownloadCV.svelte";

	import "reveal.js/dist/reveal.css";
	import "reveal.js/dist/theme/black.css";
	import "reveal.js/plugin/highlight/monokai.css";

	onMount(() => {
		const deck = new Reveal({
			autoAnimateEasing: "ease",
			autoAnimateDuration: 1,
			hash: true,
			controls: true,
			progress: true,
		});

		deck.initialize({
			plugins: [Highlight]
		});
	});
</script>

<div class="reveal">
	<div class="slides">
		<IntroductionSlide />
		<ContactSlide />
		<ExperienceSlide />
		<EducationSlide />
		<ProjectsSlide />
		<DownloadCV />
	</div>
</div>
