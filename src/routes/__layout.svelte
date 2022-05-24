<script lang="ts">
	import '../app.scss';
	import Navbar from './Navbar.svelte';
</script>

<div class="container">
	<header>
		<h1>Header</h1>
	</header>
	<Navbar />
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
