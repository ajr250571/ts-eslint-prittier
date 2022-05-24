<script lang="ts">
	let contador = 0;
	const incContador = () => {
		contador++;
	};
</script>

<h1>Inicio</h1>
<button class="btn btn-success" on:click={incContador}>{contador} Clicks</button>
