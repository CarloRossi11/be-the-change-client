<script>
	import successkid from 'images/successkid.jpg';
</script>

<style>
	* {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>Be The Change</title>
</svelte:head>

<h1>Be The Change</h1>

<figure>
	<img alt="Success Kid" src="{successkid}">
	<figcaption>Have fun with Sapper!</figcaption>
</figure>

<div>
	<h2>Volunteering Opportunites in the 412</h2>
	<p>Find your next volunteering gig here</p>
	<a href="opportunities">View Opportunities</a>
</div>