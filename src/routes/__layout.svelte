<script>
	import Header from '$lib/header/Header.svelte';
	import Footer from '$lib/Footer.svelte';
	import '../app.css';
</script>

<body class="bg-white dark:bg-slate-900">
<Header />
<main>
	<slot />
</main>

<Footer />
</body>


<style>
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 1728px;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>
