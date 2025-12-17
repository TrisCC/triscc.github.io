<script>
	import Hero from '$lib/Hero.svelte';
</script>

<svelte:head>
	<title>Tristan's Portfolio</title>
</svelte:head>

<!-- Hero Section -->
<Hero />

<header
	class="sticky top-0 z-10 bg-gray-100 dark:bg-gray-800 p-4 border-b border-gray-300 dark:border-gray-700"
>
	<nav class="flex justify-center gap-4">
		<a
			href="/"
			class="text-gray-800 dark:text-gray-200 font-medium hover:text-blue-600 dark:hover:text-blue-400"
			>Home</a
		>
		<a
			href="#projects"
			class="text-gray-800 dark:text-gray-200 font-medium hover:text-blue-600 dark:hover:text-blue-400"
			>Projects</a
		>
		<a
			href="#work-experience"
			class="text-gray-800 dark:text-gray-200 font-medium hover:text-blue-600 dark:hover:text-blue-400"
			>Work Experience</a
		>
		<a
			href="#education"
			class="text-gray-800 dark:text-gray-200 font-medium hover:text-blue-600 dark:hover:text-blue-400"
			>Education</a
		>
		<a
			href="#contact"
			class="text-gray-800 dark:text-gray-200 font-medium hover:text-blue-600 dark:hover:text-blue-400"
			>Contact</a
		>
	</nav>
</header>

<div class="p-8 bg-white dark:bg-gray-900">
	<!-- <section id="about" class="mb-8">
		<h2
			class="text-2xl font-semibold border-b-2 border-gray-300 dark:border-gray-700 pb-2 mb-4 text-gray-800 dark:text-gray-200"
		>
			About Me
		</h2>
		<p class="text-gray-700 dark:text-gray-300">
			Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut
			labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
		</p>
	</section> -->

	<section id="projects" class="mb-8">
		<h2
			class="text-2xl font-semibold border-b-2 border-gray-300 dark:border-gray-700 pb-2 mb-4 text-gray-800 dark:text-gray-200"
		>
			Projects
		</h2>
		<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
			<div
				class="border border-gray-300 dark:border-gray-700 p-6 rounded-lg bg-gray-50 dark:bg-gray-800 hover:shadow-lg transition-shadow flex overflow-hidden"
			>
				<div class="mr-6 flex flex-col grow">
					<div>
						<h3 class="text-xl font-bold mb-2 text-gray-800 dark:text-gray-200">Turff Mobile</h3>
						<p class="text-gray-700 dark:text-gray-300 mb-4">
							The Turff mobile app is a companion application for the Turff tablets, allowing users
							to manage and track their household expenses on the go.
						</p>
					</div>
					<a
						href="https://www.turff.nl/app/"
						class="inline-block text-blue-600 dark:text-blue-400 font-medium hover:underline mt-auto"
						>View Project</a
					>
				</div>
				<img
					src="/images/Turff_Mobile.jpg"
					alt="Turff Mobile App"
					class="max-w-[33%] h-full max-h-[33vh] object-cover rounded-lg"
				/>
			</div>
			<div
				class="border border-gray-300 dark:border-gray-700 p-6 rounded-lg bg-gray-50 dark:bg-gray-800 hover:shadow-lg transition-shadow flex overflow-hidden"
			>
				<div class="mr-6 flex flex-col grow">
					<div>
						<h3 class="text-xl font-bold mb-2 text-gray-800 dark:text-gray-200">Turff Tablet</h3>
						<p class="text-gray-700 dark:text-gray-300 mb-4">
							The Turff Tablet is an Android-based device designed to keep track of household
							expenses in student housing. It features a user-friendly interface that allows
							residents to log their expenses, view spending history, and manage budgets
							effectively.
						</p>
					</div>
					<a
						href="https://www.turff.nl/tablet/"
						class="inline-block text-blue-600 dark:text-blue-400 font-medium hover:underline mt-auto"
						>View Project</a
					>
				</div>
				<img
					src="/images/Turff_Tablet.jpg"
					alt="Turff Tablet"
					class="max-w-[33%] h-full max-h-[33vh] object-cover rounded-lg"
				/>
			</div>
			<div
				class="border border-gray-300 dark:border-gray-700 p-6 rounded-lg bg-gray-50 dark:bg-gray-800 hover:shadow-lg transition-shadow flex flex-col"
			>
				<div class="grow">
					<h3 class="text-xl font-bold mb-2 text-gray-800 dark:text-gray-200">
						Subreddit Language Lab
					</h3>
					<p class="text-gray-700 dark:text-gray-300 mb-4">
						The Subreddit Language Lab is a Svelte web application that visualizes language usage
						across various subreddits. It provides insights into linguistic patterns and trends
						within online communities.
					</p>
				</div>
				<a
					href="https://triscc.github.io/subreddit-language-lab/"
					class="inline-block text-blue-600 dark:text-blue-400 font-medium hover:underline mt-auto"
					>View Project</a
				>
			</div>
			<div
				class="border border-gray-300 dark:border-gray-700 p-6 rounded-lg bg-gray-50 dark:bg-gray-800 hover:shadow-lg transition-shadow flex flex-col"
			>
				<div class="grow">
					<h3 class="text-xl font-bold mb-2 text-gray-800 dark:text-gray-200">
						Clickbait Conundrum
					</h3>
					<p class="text-gray-700 dark:text-gray-300 mb-4">
						The Clickbait Conundrum is a game that challenges players to identify and avoid
						clickbait headlines. Players must navigate through a series of articles, making choices
						that test their ability to discern genuine content from sensationalized clickbait.
					</p>
				</div>
				<a
					href="https://triscc.github.io/clickbait_conundrum/#/"
					class="inline-block text-blue-600 dark:text-blue-400 font-medium hover:underline mt-auto"
					>View Project</a
				>
			</div>
			<div
				class="border border-gray-300 dark:border-gray-700 p-6 rounded-lg bg-gray-50 dark:bg-gray-800 hover:shadow-lg transition-shadow flex overflow-hidden"
			>
				<div class="mr-6 flex flex-col grow">
					<div>
						<h3 class="text-xl font-bold mb-2 text-gray-800 dark:text-gray-200">
							Creative Programming with P5.js
						</h3>
						<p class="text-gray-700 dark:text-gray-300 mb-4">
							For the Creative Programming course, I developed various interactive visualizations
							and animations using the P5.js library. These projects explored concepts such as
							generative art, user interaction, and algorithmic design.
						</p>
					</div>
					<a
						href="https://triscc.github.io/creative-programming/index.html"
						class="inline-block text-blue-600 dark:text-blue-400 font-medium hover:underline mt-auto"
						>View Project</a
					>
				</div>
				<img
					src="/images/CrePro_Kinetic.png"
					alt="Creative Programming with P5.js"
					class="max-w-[33%] h-full max-h-[33vh] object-cover rounded-lg"
				/>
			</div>
		</div>
	</section>

	<section id="work-experience" class="mb-8">
		<h2
			class="text-2xl font-semibold border-b-2 border-gray-300 dark:border-gray-700 pb-2 mb-4 text-gray-800 dark:text-gray-200"
		>
			Work Experience
		</h2>
		<div class="space-y-6">
			<div>
				<h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">
					Customer Support Representative
				</h3>
				<p class="text-md text-gray-600 dark:text-gray-400">aanmelder.nl | Apr 2025 - Present</p>
				<p class="text-gray-700 dark:text-gray-300 mt-2">
					Part of the customer support team, assisting clients with product inquiries and
					troubleshooting
				</p>
			</div>
			<div>
				<h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">Android Engineer</h3>
				<p class="text-md text-gray-600 dark:text-gray-400">Turff | Jan 2023 - Feb 2024</p>
				<p class="text-gray-700 dark:text-gray-300 mt-2">
					Responsible for the development and troubleshooting of the Turff tablet software which
					required low level Android knowledge to optimize performance and reliability.
				</p>
			</div>
			<div>
				<h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">Flutter Developer</h3>
				<p class="text-md text-gray-600 dark:text-gray-400">Turff | Jun 2021 - Dec 2022</p>
				<p class="text-gray-700 dark:text-gray-300 mt-2">
					Created the Turff mobile app using the Flutter framework in combination with libraries and
					services such as BLoC, go_router, Firebase, Sentry and Mixpanel
				</p>
			</div>
		</div>
	</section>

	<section id="education" class="mb-8">
		<h2
			class="text-2xl font-semibold border-b-2 border-gray-300 dark:border-gray-700 pb-2 mb-4 text-gray-800 dark:text-gray-200"
		>
			Education
		</h2>
		<div class="space-y-6">
			<div>
				<h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">
					MSc Creative Intelligence and Technology
				</h3>
				<p class="text-md text-gray-600 dark:text-gray-400">
					Leiden University | Sep 2025 - Jul 2027
				</p>
				<p class="text-gray-700 dark:text-gray-300 mt-2">
					Master's degree in Creative Intelligence and Technology, focusing on the intersection of
					creativity, technology, and human-centered design.
				</p>
			</div>
			<div>
				<h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">BSc Computer Science</h3>
				<p class="text-md text-gray-600 dark:text-gray-400">
					Leiden University | Sep 2020 - Jul 2025
				</p>
				<p class="text-gray-700 dark:text-gray-300 mt-2">
					Bachelor's degree in Computer Science with a minor in Digital Humanities.
				</p>
			</div>
		</div>
	</section>

	<section id="contact" class="mb-8">
		<h2
			class="text-2xl font-semibold border-b-2 border-gray-300 dark:border-gray-700 pb-2 mb-4 text-gray-800 dark:text-gray-200"
		>
			Contact
		</h2>
		<p class="text-gray-700 dark:text-gray-300">
			Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempore veniam ipsa ex beatae quidem
			voluptates explicabo iusto dignissimos unde aperiam aspernatur, quas quam laudantium eius
			sapiente autem animi. Accusamus, sapiente!
		</p>
	</section>
</div>
