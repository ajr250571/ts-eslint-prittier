<script lang="ts">
	import '../app.scss';
	import Navbar from './Navbar.svelte';

	type Config = {
		empresa: string;
		direccion: string;
	};
	let config: Config = {
		empresa: 'Panpack SA',
		direccion: 'Ruta 9 km 1304'
	};
</script>

<div class="container">
	<header>
		<h1>Header</h1>
	</header>
	<Navbar empresa={config.empresa} />
	<main>
		<slot />
	</main>
	<footer>
		<h6>Footer</h6>
	</footer>
</div>

<style lang="scss">
	header {
		padding: 10px;
		background-color: bisque;
	}
	main {
		background-color: bisque;
		padding: 10px;
	}
	footer {
		background-color: $light;
		padding: 10px;
	}
</style>
