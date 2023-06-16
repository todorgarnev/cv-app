<script lang="ts">
	import Slide from "./Slide.svelte";
</script>

<Slide animate>
	<Slide>
		<h3>My 👷 experience</h3>
	</Slide>

	<Slide animate>
		<h6 class="title">Full-stack Developer</h6>
		<p class="company">🏢 Browserbite Ltd</p>
		<p class="time-period">📆 07/2021 - Present</p>
		<p class="projects">Projects:</p>
		<ul>
			<li class="project">
				<a href="https://www.browserbite.io" target="_blank">Company website</a>
				-
				<i class="devicon-nextjs-original" title="NextJS" />
			</li>

			<li class="project">
				Warehouse management app -
				<i class="devicon-react-original" title="React" />
				<i class="devicon-typescript-plain" title="Typescript" />
				<i class="devicon-redux-original" title="Redux Toolkit" />
				<i class="devicon-nestjs-plain" title="NestJS" />
				<i class="devicon-mysql-plain" title="MySQL" />
			</li>

			<li class="project">
				Collector App (an app for a scanning warehouse device) -
				<i class="devicon-react-original" title="React" />
				<i class="devicon-typescript-plain" title="Typescript" />
			</li>

			<li class="project">
				Suppliers App related to a new German Law -
				<i class="devicon-react-original" title="React" />
				<i class="devicon-typescript-plain" title="Typescript" />
				<i class="devicon-redux-original" title="Redux Toolkit" />
				<i class="devicon-nestjs-plain" title="NestJS" />
				<i class="devicon-mysql-plain" title="MySQL" />
				<i class="devicon-electron-original" title="Electron" />
				<i class="devicon-sass-original" title="Sass" />
				<i class="devicon-tailwindcss-plain" title="Tailwind" />
			</li>

			<li class="project">
				A mobile app for picking and returning reusable tableware from restaurants -
				<i class="devicon-react-original" title="React Native" />
				<i class="devicon-tailwindcss-plain" title="Tailwind" />
			</li>

			<li class="project">
				<a href="https://www.pool-shopping.com" target="_blank">Pool shopping website</a>
				-
				<i class="devicon-react-original" title="React" />
				<i class="devicon-typescript-plain" title="Typescript" />
			</li>
		</ul>
	</Slide>

	<Slide animate>
		<h6 class="title">Frontend Developer</h6>
		<p class="company">🏢 Playtech</p>
		<p class="time-period">📆 07/2020 - 06/2021</p>
		<p class="projects">Projects:</p>
		<ul>
			<li class="project">
				Poker Web Platform -
				<i class="devicon-react-original" title="React" />
				<i class="devicon-typescript-plain" title="Typescript" />
				<i class="devicon-redux-original" title="Redux" />
			</li>
		</ul>
	</Slide>

	<Slide animate>
		<h6 class="title">Software Engineer</h6>
		<p class="company">🏢 Upnetix</p>
		<p class="time-period">📆 09/2019 - 06/2020</p>
		<p class="projects">Projects:</p>
		<ul>
			<li class="project">
				Lufthansa web platforms -

				<i class="devicon-angularjs-plain" title="Angular" />
				<i class="devicon-html5-plain" title="HTML" />
				<i class="devicon-css3-plain" title="CSS" />
				<i class="devicon-sass-original" title="Sass" />
				<i class="devicon-bootstrap-plain" title="Bootstrap" />
			</li>
		</ul>
	</Slide>

	<Slide animate>
		<h6 class="title">Junior Javascript Developer</h6>
		<p class="company">🏢 JQWidgets Ltd</p>
		<p class="time-period">📆 04/2019 - 08/2019</p>
		<p class="projects">Projects:</p>
		<ul>
			<li class="project">
				UI library -
				<i class="devicon-html5-plain" title="HTML" />
				<i class="devicon-css3-plain" title="CSS" />
				<i class="devicon-javascript-plain" title="Javascript" />
				<i class="devicon-jquery-plain" title="JQuery" />
			</li>

			<li class="project">
				Built by me -
				<a
					href="https://www.jqwidgets.com/jquery-widgets-demo/demos/jqxheatmap/index.htm"
					target="_blank"
				>
					jqxHeatMap
				</a>
			</li>
		</ul>
	</Slide>

	<Slide animate>
		<h6 class="title">Junior Software Developer</h6>
		<p class="company">🏢 Motion Software</p>
		<p class="time-period">📆 05/2018 - 03/2019</p>
		<p class="projects">Projects:</p>
		<ul>
			<li class="project">
				<a href="https://casecoach.com/coaching/" target="_blank">Coaching platform</a>
				-
				<i class="devicon-angularjs-plain" title="Angular" />
				<i class="devicon-express-original" title="Express.js" />
				<i class="devicon-mongodb-plain" title="MongoDB/Mongoose" />
			</li>

			<li class="project">
				Dating platform -
				<i class="devicon-angularjs-plain" title="Angular" />
				<i class="devicon-express-original" title="Express.js" />
				<i class="devicon-mongodb-plain" title="MongoDB/Mongoose" />
			</li>

			<li class="project">
				Crypto Statistics App -
				<i class="devicon-react-original" title="React" />
				<i class="devicon-materialui-plain" title="MaterialUI" />
			</li>

			<li class="project">
				Astrology website (Custom theme) -

				<i class="devicon-wordpress-plain" title="WordPress" />
				<i class="devicon-html5-plain" title="HTML" />
				<i class="devicon-css3-plain" title="CSS" />
			</li>
		</ul>
	</Slide>
</Slide>

<style>
	.title {
		font-size: 5rem;
	}

	.company {
		font-size: 4rem;
	}

	.time-period {
		font-size: 3rem;
	}

	.projects {
		font-size: 3rem;
		text-decoration: underline;
	}

	.project {
		margin-bottom: 1rem;
		display: flex;
		align-items: center;
		gap: 1rem;
		font-size: 2rem;
	}

	i {
		font-size: 3rem;
	}
</style>
