<svelte:head>
	<title>Lleida Esportiu</title>
	<meta name="description" content="Lleida Esportiu Football Club Landing Page" />
</svelte:head>

<section class="hero">
	<img src="/lleida-logo.png" alt="Lleida Esportiu Logo" />
	<h1>Benvinguts al Lleida Esportiu</h1>
	<p>El club de futbol de la Terra Ferma</p>
</section>

<section class="team-info">
	<h2>El nostre equip</h2>
	<p>Aquí hi anirà informació sobre el club, la seva història, palmarès, etc.</p>
</section>

<footer>
	<p>Segueix-nos a les xarxes socials</p>
	<div class="social-links">
		<a href="https://www.facebook.com/Club_Lleida-Esportiu-102625282366950" target="_blank">Facebook</a>
		<a href="https://twitter.com/SalvarLleidaEsp" target="_blank">Twitter</a>
		<a href="https://www.instagram.com/salvarlleidaesportiu/" target="_blank">Instagram</a>
		<a href="https://www.youtube.com/@ClubLleidaEsportiu" target="_blank">YouTube</a>
	</div>
</footer>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');

	:global(body) {
		font-family: 'Montserrat', sans-serif;
		background-color: #f0f4f8;
		color: #333;
	}

	.hero {
		text-align: center;
		padding: 4rem 1rem;
		background-color: #000080;
		color: white;
	}

	.hero img {
		width: 150px;
		margin-bottom: 1rem;
	}

	.hero h1 {
		font-size: 3rem;
		margin-bottom: 0.5rem;
	}

	.team-info {
		padding: 2rem 1rem;
		text-align: center;
	}

	footer {
		text-align: center;
		padding: 2rem 1rem;
		background-color: #000080;
		color: white;
	}

	.social-links a {
		color: white;
		margin: 0 0.5rem;
		text-decoration: none;
	}

	.social-links a:hover {
		text-decoration: underline;
	}
</style>
