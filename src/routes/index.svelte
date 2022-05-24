<script lang="ts">
	let contador = 0;
	const incContador = () => {
		contador++;
	};
</script>

<h1>Inicio 📇</h1>
<div class="container d-flex align-items-center justify-content-center  vh-70">
	<div class="row">
		<div class="col-12 col-lg-9">
			<div class="row">
				<div class="col-12 col-lg-8 bg-primary">
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi dolorem a ab sed dolorum
					quae qui magnam veritatis molestias odio.
				</div>
				<div class="col-12  col-lg-4 bg-secondary">
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi dolorem a ab sed dolorum
					quae qui magnam veritatis molestias odio.
				</div>
				<div class="col-12  col-lg-4 bg-warning">
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi dolorem a ab sed dolorum
					quae qui magnam veritatis molestias odio.
				</div>
				<div class="col-12  col-lg-8 bg-success">
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi dolorem a ab sed dolorum
					quae qui magnam veritatis molestias odio.
				</div>
			</div>
		</div>
		<div class="col-12 col-lg-3 bg-info">
			Lorem ipsum dolor sit amet, consectetur adipisicing elit. Odit iure voluptatem tenetur
			expedita ducimus omnis itaque in assumenda! Ipsa praesentium labore ipsum laboriosam rerum in
			ad est porro! Officiis, aliquid?
		</div>
	</div>
</div>
<div class="row">
	<div class="col-4 mt-2">
		<button class="btn btn-success align-middle" on:click={incContador}>{contador} Clicks</button>
	</div>
</div>
