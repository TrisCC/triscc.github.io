<svelte:head>
	<title>Tristan's Portfolio</title>
</svelte:head>

<h1>Tristan Cotino</h1>
<p>Welcome to my personal portfolio</p>

<section id="about">
	<h2>About Me</h2>
	<p>
		Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut
		labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
	</p>
</section>

<section id="projects">
	<h2>Projects</h2>
	<div class="projects-grid">
		<div class="project-card">
			<h3>Project 1</h3>
			<p>
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium vel officia adipisci
				dolore autem sed illo, et dolor quaerat maiores, enim aperiam in exercitationem obcaecati
				recusandae ad, minus quasi nobis?
			</p>
			<a href="#" class="project-link">View Project</a>
		</div>
		<div class="project-card">
			<h3>Project 2</h3>
			<p>
				Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptatem nesciunt quae dolor
				earum illo cupiditate, corporis atque error ratione. Odit maiores rem consectetur tenetur ab
				error maxime hic laboriosam blanditiis.
			</p>
			<a href="#" class="project-link">View Project</a>
		</div>
		<div class="project-card">
			<h3>Project 3</h3>
			<p>
				Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquam eveniet consequuntur
				praesentium culpa, delectus eum voluptate veritatis ut voluptates rerum, dolore quis facilis
				tenetur cupiditate libero doloremque maxime. Repellendus, consequatur?
			</p>
			<a href="#" class="project-link">View Project</a>
		</div>
	</div>
</section>

<section id="contact">
	<h2>Contact</h2>
	<p>
		Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempore veniam ipsa ex beatae quidem
		voluptates explicabo iusto dignissimos unde aperiam aspernatur, quas quam laudantium eius
		sapiente autem animi. Accusamus, sapiente!
	</p>
</section>

<style>
	section {
		margin-bottom: 2rem;
	}

	h2 {
		border-bottom: 2px solid #ddd;
		padding-bottom: 0.5rem;
		margin-bottom: 1rem;
	}

	.projects-grid {
		display: grid;
		grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
		gap: 1.5rem;
	}

	.project-card {
		border: 1px solid #ddd;
		padding: 1.5rem;
		border-radius: 8px;
		background: #f9f9f9;
		transition: transform 0.2s;
	}

	.project-card:hover {
		transform: translateY(-5px);
	}

	.project-card h3 {
		margin-top: 0;
	}

	.project-link {
		display: inline-block;
		margin-top: 1rem;
		text-decoration: none;
		color: #007bff;
		font-weight: 500;
	}
</style>
