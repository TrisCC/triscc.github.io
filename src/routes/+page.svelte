<svelte:head>
	<title>Tristan's Portfolio</title>
</svelte:head>

<div class="w-full bg-gray-200 h-[33vh] flex items-center justify-center">
	<h1 class="text-6xl font-bold text-gray-800">Tristan Cotino</h1>
</div>

<div class="p-8">
	<section id="about" class="mb-8">
		<h2 class="text-2xl font-semibold border-b-2 border-gray-300 pb-2 mb-4">About Me</h2>
		<p class="text-gray-700">
			Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut
			labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
		</p>
	</section>

	<section id="projects" class="mb-8">
		<h2 class="text-2xl font-semibold border-b-2 border-gray-300 pb-2 mb-4">Projects</h2>
		<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
			<div
				class="border border-gray-300 p-6 rounded-lg bg-gray-50 hover:shadow-lg transition-shadow"
			>
				<h3 class="text-xl font-bold mb-2">Turff Mobile</h3>
				<p class="text-gray-700 mb-4">
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium vel officia adipisci
					dolore autem sed illo, et dolor quaerat maiores, enim aperiam in exercitationem obcaecati
					recusandae ad, minus quasi nobis?
				</p>
				<button class="inline-block text-blue-600 font-medium hover:underline" type="button"
					>View Project</button
				>
			</div>
			<div
				class="border border-gray-300 p-6 rounded-lg bg-gray-50 hover:shadow-lg transition-shadow"
			>
				<h3 class="text-xl font-bold mb-2">Turff Tablets</h3>
				<p class="text-gray-700 mb-4">
					Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptatem nesciunt quae dolor
					earum illo cupiditate, corporis atque error ratione. Odit maiores rem consectetur tenetur
					ab error maxime hic laboriosam blanditiis.
				</p>
				<button class="inline-block text-blue-600 font-medium hover:underline" type="button"
					>View Project</button
				>
			</div>
			<div
				class="border border-gray-300 p-6 rounded-lg bg-gray-50 hover:shadow-lg transition-shadow"
			>
				<h3 class="text-xl font-bold mb-2">Subreddit Language Lab</h3>
				<p class="text-gray-700 mb-4">
					Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquam eveniet consequuntur
					praesentium culpa, delectus eum voluptate veritatis ut voluptates rerum, dolore quis
					facilis tenetur cupiditate libero doloremque maxime. Repellendus, consequatur?
				</p>
				<button class="inline-block text-blue-600 font-medium hover:underline" type="button"
					>View Project</button
				>
			</div>
			<div
				class="border border-gray-300 p-6 rounded-lg bg-gray-50 hover:shadow-lg transition-shadow"
			>
				<h3 class="text-xl font-bold mb-2">Clickbait Conundrum</h3>
				<p class="text-gray-700 mb-4">
					Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquam eveniet consequuntur
					praesentium culpa, delectus eum voluptate veritatis ut voluptates rerum, dolore quis
					facilis tenetur cupiditate libero doloremque maxime. Repellendus, consequatur?
				</p>
				<button class="inline-block text-blue-600 font-medium hover:underline" type="button"
					>View Project</button
				>
			</div>
		</div>
	</section>

	<section id="work-experience" class="mb-8">
		<h2 class="text-2xl font-semibold border-b-2 border-gray-300 pb-2 mb-4">Work Experience</h2>
		<div class="space-y-6">
			<div>
				<h3 class="text-xl font-bold">Customer Support Representative</h3>
				<p class="text-md text-gray-600">aanmelder.nl | Apr 2025 - Present</p>
				<p class="text-gray-700 mt-2">
					Part of the customer support team, assisting clients with product inquiries and
					troubleshooting
				</p>
			</div>
			<div>
				<h3 class="text-xl font-bold">Android Engineer</h3>
				<p class="text-md text-gray-600">Turff | Jan 2023 - Feb 2024</p>
				<p class="text-gray-700 mt-2">
					Responsible for the development and troubleshooting of the Turff tablet software which
					required low level Android knowledge to optimize performance and reliability.
				</p>
			</div>
			<div>
				<h3 class="text-xl font-bold">Flutter Developer</h3>
				<p class="text-md text-gray-600">Turff | Jun 2021 - Dec 2022</p>
				<p class="text-gray-700 mt-2">
					Created the Turff mobile app using the Flutter framework in combination with libraries and
					services such as BLoC, go_router, Firebase, Sentry and Mixpanel
				</p>
			</div>
		</div>
	</section>

	<section id="contact" class="mb-8">
		<h2 class="text-2xl font-semibold border-b-2 border-gray-300 pb-2 mb-4">Contact</h2>
		<p class="text-gray-700">
			Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempore veniam ipsa ex beatae quidem
			voluptates explicabo iusto dignissimos unde aperiam aspernatur, quas quam laudantium eius
			sapiente autem animi. Accusamus, sapiente!
		</p>
	</section>
</div>
