<script lang="ts">
	import '../app.scss';
	import Contactos from './contactos.svelte';
	import Header from './header.svelte';
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
	<Header {...config} />
	<Navbar />
	<main>
		<slot />
	</main>
	<footer>
		<h6>Footer</h6>
	</footer>
</div>

<style lang="scss">
	main {
		background-color: bisque;
		padding: 10px;
	}
	footer {
		background-color: $light;
		padding: 10px;
	}
</style>
