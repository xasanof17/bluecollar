<script>
	import edit from './img/edit.svg';
	import house from './img/house.svg';
	import electrical from './img/electrical.svg';
	import security from './img/security.svg';
	import service from './img/service.svg';
	import air from './img/air.svg';
	import yellowCommercial from './img/yellow-commercial.svg';
</script>

<section class="skills">
	<div class="container">
		<div class="skills__content">
			<div class="skills__content-top">
				<div class="skills__content-top_area">
					<img src={edit} alt="edit" />
					<p>Area Of Service</p>
				</div>
				<div class="skills__content-top_center">
					<h2>Our Services</h2>
					<p>
						We offers a comprehensive range of electrical services for domestic and commercial
						properties at a reasonable price.
					</p>
				</div>
			</div>
			<div class="skills__content-cards">
				<div class="row skills__content-cards_block">
					<div class="col-12 col-lg-4 col-md-6 skills__content-cards_block-card">
						<div class="skills__content-cards_block-card_inner">
							<img src={air} alt="img" />
							<h3>Air condition service</h3>
							<p>
								Services are able to service your entire electrical infrastructure from Thermal
								Imaging of your air condition from switch boards.
							</p>
							<a href="#!">View More</a>
						</div>
					</div>
					<div class="col-12 col-lg-4 col-md-6 skills__content-cards_block-card">
						<div class="skills__content-cards_block-card_inner">
							<img src={electrical} alt="img" />
							<h3>Electrical installation</h3>
							<p>
								The art electrical installations that provide all the necessary electrical solutions
								to suit your business, home or industrial premises.
							</p>
							<a href="#!">View More</a>
						</div>
					</div>
					<div class="col-12 col-lg-4 col-md-6 skills__content-cards_block-card">
						<div class="skills__content-cards_block-card_inner">
							<img src={yellowCommercial} alt="img" />
							<h3>General Builder</h3>
							<p>
								We provide impeccable safety assessments to both commercial, residential properties.
								Our adept & knowledgeable electricians.
							</p>
							<a href="#!">View More</a>
						</div>
					</div>
					<div class="col-12 col-lg-4 col-md-6 skills__content-cards_block-card">
						<div class="skills__content-cards_block-card_inner">
							<img src={security} alt="img" />
							<h3>Security System</h3>
							<p>
								Utilized for measuring flow, temperature level & pressure in the manufacturing
								industry array of technology is ensure productivity.
							</p>
							<a href="#!">View More</a>
						</div>
					</div>
					<div class="col-12 col-lg-4 col-md-6 skills__content-cards_block-card">
						<div class="skills__content-cards_block-card_inner">
							<img src={service} alt="img" />
							<h3>Service & maintenance</h3>
							<p>
								Electrical Services are able to service your entire electrical infrastructure from
								Thermal Imaging of your switch boards.
							</p>
							<a href="#!">View More</a>
						</div>
					</div>
					<div class="col-12 col-lg-4 col-md-6 skills__content-cards_block-card">
						<div class="skills__content-cards_block-card_inner">
							<img src={house} alt="img" />
							<h3>House Extensions</h3>
							<p>
								Traditionally, electricity is supplied through overhead network poles, where the
								cable is connected to your building.
							</p>
							<a href="#!">View More</a>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<style lang="scss" scoped>
	.skills {
		margin: 250px 0 140px 0;
		&__content {
			&-top {
				display: flex;
				align-items: center;
				justify-content: center;
				flex-direction: column;
				&_area {
					display: flex;
					align-items: center;
					padding: 0 20px;
					background: var(--white);
					img {
						margin-right: 10px;
						pointer-events: none;
						user-select: none;
					}
				}
				&_center {
					display: flex;
					align-items: center;
					justify-content: center;
					flex-direction: column;
					margin-top: 20px;
					h2 {
						font-weight: 400;
						font-size: 45px;
						line-height: 58px;
						letter-spacing: 0.36px;
						color: var(--blue);
						margin-bottom: 12px;
					}
					p {
						max-width: 819px;
						width: 100%;
						font-weight: 400;
						font-size: 18px;
						line-height: 27px;
						text-align: center;
						letter-spacing: 0.36px;
						color: var(--grey);
					}
				}
			}
			&-cards {
				margin-top: 50px;
				&_block {
					display: flex;
					align-items: center;
					justify-content: center;
					&-card {
						max-width: 400px;
						width: 100%;
						min-height: 378px;
						height: 100%;
						background: var(--blue);
						margin: 15px;
						padding: 50px 40px;
						&_inner {
							img {
								user-select: none;
								pointer-events: none;
								width: 50px;
								height: 50px;
								margin-bottom: 22px;
							}
							h3 {
								font-weight: 400;
								font-size: 25px;
								line-height: 38px;
								letter-spacing: 0.36px;
								text-transform: capitalize;
								color: var(--yellow);
								margin-bottom: 15px;
							}
							p {
								font-weight: 400;
								font-size: 18px;
								line-height: 27px;
								color: var(--grey2);
								letter-spacing: 0.36px;
								margin-bottom: 22px;
							}
							a {
								font-weight: 400;
								font-size: 18px;
								line-height: 27px;
								letter-spacing: 0.36px;
								color: var(--white);
								&:hover{
									text-decoration: underline;
								}
							}
						}
					}
				}
			}
		}
	}
</style>
