<!-- Footer.svelte -->
<footer>
	<a href="/">Home</a>

	<nav>
		<ul>
			<li>
				<a href="/about">About</a>
			</li>
			<li>
				<a href="/contact">Contact</a>
			</li>
		</ul>
	</nav>
</footer>

<style>
	footer {
		padding: 1rem;
		background: lightskyblue;
		display: flex;
		flex-wrap: wrap;
		justify-content: space-between;
	}

	ul {
		margin: 0;
		list-style-type: none;
		display: flex;
		gap: 1rem;
	}

	a {
		text-decoration: none;
		color: inherit;
	}
</style>