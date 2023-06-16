<script lang="ts">
	import Slide from "./Slide.svelte";
</script>

<Slide animate>
	<Slide>
		<h3>My 📖 education</h3>
	</Slide>

	<Slide animate>
		<h6 class="title">Bachelor's degree in Computer Systems</h6>
		<p class="uni">🏫 Technical University of Sofia</p>
		<p class="time-period">📆 09/2011 - 05/2015</p>
	</Slide>

	<Slide animate>
		<h6 class="title">Front-end Course</h6>
		<p class="uni">🏫 Swift Academy</p>
		<p class="time-period">📆 09/2017 - 01/2018</p>
		<a href="http://swift.bg/certificates/todorivanovgarnev/e1329cbc.pdf" target="_blank">
			📜
		</a>
	</Slide>

	<Slide animate>
		<h6 class="title">React Fundamentals</h6>
		<p class="uni">🏫 Software University</p>
		<a href="https://softuni.bg/certificates/details/56304/87f9d0ad" target="_blank">
			📜
		</a>
	</Slide>
</Slide>

<style>
	.title {
		font-size: 5rem;
	}

	.uni {
		font-size: 4rem;
	}

	.time-period {
		font-size: 3rem;
	}
</style>
