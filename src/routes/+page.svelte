<svelte:head>
	<title>4ui</title>
	<meta
		name="description"
		content="Open-code Svelte components for operational and data-heavy interfaces."
	/>
</svelte:head>

<main>
	<p>4ui</p>
	<h1>The component library is taking shape.</h1>
	<p>
		Accessible Svelte 5 foundations for operational software, realtime data, and industrial
		interfaces.
	</p>
</main>

<style>
	:global(*) {
		box-sizing: border-box;
	}

	:global(body) {
		margin: 0;
		font-family:
			Inter,
			ui-sans-serif,
			system-ui,
			-apple-system,
			BlinkMacSystemFont,
			'Segoe UI',
			sans-serif;
		background: #f7f7f8;
		color: #171719;
	}

	main {
		display: grid;
		align-content: center;
		min-height: 100vh;
		max-width: 720px;
		margin: 0 auto;
		padding: 48px 24px;
	}

	p {
		max-width: 62ch;
		margin: 0;
		color: #56565c;
		font-size: 1rem;
		line-height: 1.65;
	}

	main > p:first-child {
		margin-bottom: 20px;
		color: #171719;
		font-weight: 700;
	}

	h1 {
		max-width: 12ch;
		margin: 0 0 24px;
		font-size: clamp(2.5rem, 8vw, 5.5rem);
		line-height: 0.96;
		letter-spacing: -0.04em;
		text-wrap: balance;
	}
</style>
