<svelte:head>
	<title>Tristan's Portfolio</title>
</svelte:head>

<div class="w-full bg-gray-200 h-[33vh] flex items-center justify-center">
	<h1 class="text-6xl font-bold text-gray-800">Tristan Cotino</h1>
</div>

<div class="p-8">
	<p class="text-lg text-gray-600 mb-8 text-center">Welcome to my personal portfolio</p>

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
				<h3 class="text-xl font-bold mb-2">Project 1</h3>
				<p class="text-gray-700 mb-4">
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium vel officia adipisci
					dolore autem sed illo, et dolor quaerat maiores, enim aperiam in exercitationem obcaecati
					recusandae ad, minus quasi nobis?
				</p>
				<a href="#" class="inline-block text-blue-600 font-medium hover:underline">View Project</a>
			</div>
			<div
				class="border border-gray-300 p-6 rounded-lg bg-gray-50 hover:shadow-lg transition-shadow"
			>
				<h3 class="text-xl font-bold mb-2">Project 2</h3>
				<p class="text-gray-700 mb-4">
					Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptatem nesciunt quae dolor
					earum illo cupiditate, corporis atque error ratione. Odit maiores rem consectetur tenetur
					ab error maxime hic laboriosam blanditiis.
				</p>
				<a href="#" class="inline-block text-blue-600 font-medium hover:underline">View Project</a>
			</div>
			<div
				class="border border-gray-300 p-6 rounded-lg bg-gray-50 hover:shadow-lg transition-shadow"
			>
				<h3 class="text-xl font-bold mb-2">Project 3</h3>
				<p class="text-gray-700 mb-4">
					Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquam eveniet consequuntur
					praesentium culpa, delectus eum voluptate veritatis ut voluptates rerum, dolore quis
					facilis tenetur cupiditate libero doloremque maxime. Repellendus, consequatur?
				</p>
				<a href="#" class="inline-block text-blue-600 font-medium hover:underline">View Project</a>
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
