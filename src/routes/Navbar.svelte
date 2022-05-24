<script lang="ts">
	export let empresa='Nombre Empresa';
</script>

<nav class="navbar navbar-expand-xl navbar-light bg-light">
	<a class="navbar-brand" href="/">{empresa}</a>
	<button
		class="navbar-toggler d-lg-none"
		type="button"
		data-bs-toggle="collapse"
		data-bs-target="#collapsibleNavId"
		aria-controls="collapsibleNavId"
		aria-expanded="false"
		aria-label="Toggle navigation"
	>
		<span class="navbar-toggler-icon" />
	</button>
	<div class="collapse navbar-collapse" id="collapsibleNavId">
		<ul class="navbar-nav me-auto mt-2 mt-lg-0">
			<li class="nav-item">
				<a class="nav-link" href="/">Inicio</a>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="/empresa">Empresa</a>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="/productos">Productos</a>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="/contactos">Contactos</a>
			</li>
		</ul>
		<form class="d-flex my-2 my-lg-0">
			<input class="form-control me-sm-2" type="text" placeholder="Buscar" />
			<button class="btn btn-outline-success my-2 my-sm-0" type="submit">Buscar</button>
		</form>
	</div>
</nav>

<style lang="scss">
	nav {
		padding: 10px;
	}
</style>
