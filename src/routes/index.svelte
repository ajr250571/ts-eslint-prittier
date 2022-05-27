<script lang="ts">
	import img_caty from '../imagenes/caty.jpg';
</script>

<div class="container align-items-center justify-content-center  alto-100">
	<div class="row">
		<div class="col-12 col-lg-9">
			<div class="row">
				<div class="col-12 col-lg-8 p-2">
					<article class="card h-100 bg-primary">
						<div class="card-body">
							<div class="d-flex">
								<img
									id="img_size"
									src={img_caty}
									class="img-fluid rounded-circle border border-secondary border-3"
									alt="Caty"
								/>
								<div class="m-0 ps-3">
									<h6>Caty Lourdes</h6>
									<p>Lorem, ipsum dolor sit.</p>
								</div>
							</div>
							<div>
								<p class="fs-6 lh-1">
									Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet qui labore rem
									cupiditate magnam, iste dolores vero
								</p>
							</div>
						</div>
					</article>
				</div>
				<div class="col-12  col-lg-4 p-2">
					<article class="card h-100 bg-secondary">
						<div class="card-body">
							<div class="d-flex">
								<img
									id="img_size"
									src={img_caty}
									class="img-fluid rounded-circle border border-secondary border-3"
									alt="Caty"
								/>
								<div class="m-0 ps-3">
									<h6>Caty Lourdes</h6>
									<p>Lorem, ipsum dolor sit.</p>
								</div>
							</div>
							<div>
								<p class="fs-6 lh-1">
									Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet qui labore rem
									cupiditate magnam
								</p>
							</div>
						</div>
					</article>
				</div>
				<div class="col-12  col-lg-4 p-2">
					<article class="card bg-warning h-100">
						<div class="card-body">
							<div class="d-flex">
								<img
									id="img_size"
									src={img_caty}
									class="img-fluid rounded-circle border border-secondary border-3"
									alt="Caty"
								/>
								<div class="m-0 ps-3">
									<h6>Caty Lourdes</h6>
									<p>Lorem, ipsum dolor sit.</p>
								</div>
							</div>
							<div>
								<p class="fs-6 lh-1">
									Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet qui labore rem
									cupiditate magnam
								</p>
							</div>
						</div>
					</article>
				</div>
				<div class="col-12  col-lg-8 p-2">
					<article class="card bg-success h-100">
						<div class="card-body">
							<div class="d-flex">
								<img
									src={img_caty}
									id="img_size"
									class="img-fluid rounded-circle border border-secondary border-3"
									alt="Caty"
								/>
								<div class="m-0 ps-3">
									<h6>Caty Lourdes</h6>
									<p>Lorem, ipsum dolor sit.</p>
								</div>
							</div>
							<div>
								<p class="fs-6 lh-1">
									Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet qui labore rem
									cupiditate magnam
								</p>
							</div>
						</div>
					</article>
				</div>
			</div>
		</div>
		<div class="col-12 col-lg-3 p-2">
			<article class="card bg-info h-100">
				<div class="card-body">
					<div class="d-flex">
						<img
							src={img_caty}
							id="img_size"
							class="img-fluid rounded-circle border border-secondary border-3"
							alt="Caty"
						/>
						<div class="m-0 ps-3">
							<h6>Caty Lourdes</h6>
							<p>Lorem, ipsum dolor sit amet.</p>
						</div>
					</div>
					<div>
						<p class="fs-6 lh-1">
							Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet qui labore rem
							cupiditate magnam, iste dolores vero porro veritatis accusantium distinctio autem
							temporibus repellat, similique, odio quidem assumenda impedit ab!
						</p>
					</div>
				</div>
			</article>
		</div>
	</div>
</div>

<style lang="scss">
	@media (min-width: 92px) {
		.alto-100 {
			height: 100vh;
		}
	}
	#img_size {
		width: 50px;
		height: 50px;
	}
</style>
