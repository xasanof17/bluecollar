<script>
	import edit from './img/edit.svg';
	import card1 from './img/card1.svg';
	import card2 from './img/card2.svg';
	import card3 from './img/card3.svg';
	import card4 from './img/card4.svg';
</script>

<section class="gallery">
	<div class="container">
		<div class="gallery__content">
			<div class="gallery__content-top">
				<div class="gallery__content-top_inner">
					<img src={edit} alt="icon" />
					<p>The Gallery</p>
				</div>
				<h2>Our Recent Projects</h2>
			</div>
			<div class="row gallery__content-cards">
				<div class="col-12 col-lg-3 col-md-6 gallery__content-cards_card">
					<div class="gallery__content-cards_card-inner">
						<div class="gallery__content-cards_card-inner_img">
							<img src={card1} alt="img" />
						</div>
						<div class="gallery__content-cards_card-inner_body">
							<h3>Fiber cable change</h3>
							<span>Commercial</span>
						</div>
					</div>
				</div>
				<div class="col-12 col-lg-3 col-md-6 gallery__content-cards_card">
					<div class="gallery__content-cards_card-inner">
						<div class="gallery__content-cards_card-inner_img">
							<img src={card2} alt="img" />
						</div>
						<div class="gallery__content-cards_card-inner_body">
							<h3>Industry machine issue</h3>
							<span>Industry</span>
						</div>
					</div>
				</div>
				<div class="col-12 col-lg-3 col-md-6 gallery__content-cards_card">
					<div class="gallery__content-cards_card-inner">
						<div class="gallery__content-cards_card-inner_img">
							<img src={card3} alt="img" />
						</div>
						<div class="gallery__content-cards_card-inner_body">
							<h3>Wheel Alloy Change</h3>
							<span>Residential</span>
						</div>
					</div>
				</div>
				<div class="col-12 col-lg-3 col-md-6 gallery__content-cards_card">
					<div class="gallery__content-cards_card-inner">
						<div class="gallery__content-cards_card-inner_img">
							<img src={card4} alt="img" />
						</div>
						<div class="gallery__content-cards_card-inner_body">
							<h3>Roof Cleaning</h3>
							<span>Commercial</span>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<style lang="scss" scoped>
	.gallery {
		background: var(--blue);
		&__content {
			padding: 150px 0;
			&-top {
				display: flex;
				align-items: center;
				justify-content: center;
				flex-direction: column;
				&_inner {
					padding: 0 20px;
					background: var(--light);
					display: flex;
					align-items: center;
					img {
						pointer-events: none;
						user-select: none;
						margin-right: 10px;
					}
					p {
						font-weight: 400;
						font-size: 18px;
						line-height: 27px;
						text-align: center;
						letter-spacing: 0.36px;
						text-transform: capitalize;
						color: var(--blue);
					}
				}
				h2 {
					font-weight: 400;
					font-size: 45px;
					line-height: 58px;
					letter-spacing: 0.36px;
					color: var(--white);
					margin-top: 22px;
				}
			}
			&-cards {
				margin-top: 50px;
				&_card {
					&-inner {
						padding: 20px 20px 30px 20px;
						background: var(--grey2);
						&_img {
							img {
								pointer-events: none;
								user-select: none;
								height: 100%;
								width: 100%;
							}
						}
						&_body {
							margin-top: 30px;
							display: flex;
							align-items: center;
							justify-content: center;
							flex-direction: column;
							h3 {
								font-weight: 400;
								font-size: 25px;
								line-height: 38px;
								text-align: center;
								letter-spacing: 0.36px;
								text-transform: capitalize;
								color: var(--blue);
							}
							span {
								font-weight: 400;
								font-size: 17px;
								line-height: 27px;
								text-align: center;
								letter-spacing: 0.36px;
								color: var(--grey);
							}
						}
					}
				}
			}
		}
	}
</style>
