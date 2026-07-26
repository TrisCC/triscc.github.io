<script>
	import Hero from '$lib/Hero.svelte';
</script>

<svelte:head>
	<title>Tristan's Portfolio</title>
</svelte:head>

<!-- Hero Section -->
<Hero />

<!-- Navigation Bar -->
<header
	class="sticky top-0 z-10 bg-gray-100 dark:bg-gray-800 p-4 border-b border-gray-300 dark:border-gray-700"
>
	<nav class="flex justify-center gap-4">
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

<!-- Content -->
<div class="p-8 bg-white dark:bg-gray-900">
	<div class="max-w-7xl mx-auto">
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
							<h3 class="text-xl font-bold mb-2 text-gray-800 dark:text-gray-200">Odd Bird Out</h3>
							<p class="text-gray-700 dark:text-gray-300 mb-4">
								OddBirdOut is a three-player interactive game installation made for an art exhibition. The installation aims to explore the topic of cyber ostracism, which is the experience of feeling digitally excluded even when no one is actually rejecting you. Three players stand at a triangular structure, each using an Android tablet separated by panels so they cannot see each other. The game has players act as ostriches trying to collect eggs by choosing a partner to pair up with. Throughout the game, the players will face the fact that exclusion is not always personal and that the feeling of being ostracized is very easily triggered.
							</p>
						</div>
						<a
							href="https://triscc.github.io/OddBirdOut/"
							class="inline-block text-blue-600 dark:text-blue-400 font-medium hover:underline mt-auto"
							>View Project</a
						>
					</div>
					<img
						src="/images/oddbirdout.png"
						alt="Odd Bird Out"
						class="max-w-[33%] h-full max-h-[33vh] object-cover rounded-lg"
					/>
				</div>
				<div
					class="border border-gray-300 dark:border-gray-700 p-6 rounded-lg bg-gray-50 dark:bg-gray-800 hover:shadow-lg transition-shadow flex overflow-hidden"
				>
					<div class="mr-6 flex flex-col grow">
						<div>
							<h3 class="text-xl font-bold mb-2 text-gray-800 dark:text-gray-200">Turff Mobile</h3>
							<p class="text-gray-700 dark:text-gray-300 mb-4">
								The Turff mobile app is a companion application for the Turff tablets, allowing
								users to manage and track their household expenses on the go.
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
					class="border border-gray-300 dark:border-gray-700 p-6 rounded-lg bg-gray-50 dark:bg-gray-800 hover:shadow-lg transition-shadow flex overflow-hidden"
				>
					<div class="mr-6 flex flex-col grow">
						<div>
							<h3 class="text-xl font-bold mb-2 text-gray-800 dark:text-gray-200">
								Subreddit Language Lab
							</h3>
							<p class="text-gray-700 dark:text-gray-300 mb-4">
								The Subreddit Language Lab is a Svelte web application that visualizes language
								usage across various subreddits. It provides insights into linguistic patterns and
								trends within online communities.
							</p>
						</div>
						<a
							href="https://triscc.github.io/subreddit-language-lab/"
							class="inline-block text-blue-600 dark:text-blue-400 font-medium hover:underline mt-auto"
							>View Project</a
						>
					</div>
					<img
						src="/images/SubredditLanguageLab.png"
						alt="Subreddit Language Lab"
						class="max-w-[33%] h-full max-h-[33vh] object-cover rounded-lg"
					/>
				</div>
				<div
					class="border border-gray-300 dark:border-gray-700 p-6 rounded-lg bg-gray-50 dark:bg-gray-800 hover:shadow-lg transition-shadow flex overflow-hidden"
				>
					<div class="mr-6 flex flex-col grow">
						<div>
							<h3 class="text-xl font-bold mb-2 text-gray-800 dark:text-gray-200">
								Clickbait Conundrum
							</h3>
							<p class="text-gray-700 dark:text-gray-300 mb-4">
								The Clickbait Conundrum is a game that challenges players to identify and avoid
								clickbait headlines. Players must navigate through a series of articles, making
								choices that test their ability to discern genuine content from sensationalized
								clickbait.
							</p>
						</div>
						<a
							href="https://triscc.github.io/clickbait_conundrum/#/"
							class="inline-block text-blue-600 dark:text-blue-400 font-medium hover:underline mt-auto"
							>View Project</a
						>
					</div>
					<img
						src="/images/ClickbaitConundrum.png"
						alt="Clickbait Conundrum"
						class="max-w-[33%] h-full max-h-[33vh] object-cover rounded-lg"
					/>
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
					<h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">Android and iOS Developer</h3>
					<p class="text-md text-gray-600 dark:text-gray-400">9to5 software | Jan 2026 - Present</p>
					<p class="text-gray-700 dark:text-gray-300 mt-2">
						Responsible for the development of multiple native in-house and client Android and iOS apps written in
						Kotlin and Swift.
					</p>
				</div>
				<div>
					<h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">
						Customer Support Representative
					</h3>
					<p class="text-md text-gray-600 dark:text-gray-400">aanmelder.nl | Apr 2025 - Dec 2025</p>
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
						Created the Turff mobile app using the Flutter framework in combination with libraries
						and services such as BLoC, go_router, Firebase, Sentry and Mixpanel
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
						Leiden University | Sep 2019 - Jul 2025
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
			<div class="flex gap-4">
				<a
					href="https://www.linkedin.com/in/tristancotino/"
					target="_blank"
					rel="noopener noreferrer"
					class="inline-flex items-center bg-blue-600 dark:bg-blue-500 text-white font-medium py-2 px-4 rounded-lg hover:bg-blue-700 dark:hover:bg-blue-600 transition-colors"
				>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						class="h-5 w-5 mr-2"
						fill="currentColor"
						viewBox="0 0 24 24"
					>
						<path
							d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"
						/>
					</svg>
					LinkedIn
				</a>
				<a
					href="https://github.com/TrisCC"
					target="_blank"
					rel="noopener noreferrer"
					class="inline-flex items-center bg-gray-200 dark:bg-gray-700 text-gray-800 dark:text-gray-200 font-medium py-2 px-4 rounded-lg hover:bg-gray-300 dark:hover:bg-gray-600 transition-colors"
				>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						class="h-5 w-5 mr-2"
						fill="currentColor"
						viewBox="0 0 24 24"
					>
						<path
							d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.91 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"
						/>
					</svg>
					GitHub
				</a>
			</div>
		</section>
	</div>
</div>
