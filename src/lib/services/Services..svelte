<script>
	import icon from './img/main-icon.svg';
	import commercial from './img/commercial.svg';
	import yellowCommercial from './img/yellow-commercial.svg';
	import industrial from './img/industrial.svg';
	import resedential from './img/resedential.svg';
    import img2 from './img/img2.svg';
</script>

<section class="service">
	<div class="container">
		<div class="service__content">
			<div class="row">
				<div class="service__content-top col-12">
					<div class="service__content-top_box">
						<div class="service__content-top_box-top">
							<img src={icon} alt="icon" />
							<p>What We Offer</p>
						</div>
						<div class="service__content-top_box-center">
							<h2>Professional Main Services</h2>
							<p>
								We have extensive experience of domestic and business electrical installations and
								no job is too small. Our customers value our professionalism, work ethic and our
								competitive prices.
							</p>
						</div>
						<div class="service__content-top_box-buttons">
							<div class="row service__content-top_box-buttons_content">
								<button
									class="col-12 col-lg-3 col-md-4 col-sm-4 service__content-top_box-buttons_content-btn active"
								>
									<img src={commercial} alt="icon" />
									<p>Commercial</p>
								</button>
								<button
									class="col-12 col-lg-3 col-md-4 col-sm-4 service__content-top_box-buttons_content-btn"
								>
									<img src={resedential} alt="icon" />
									<p>Residential</p>
								</button>
								<button
									class="col-12 col-lg-3 col-md-4 col-sm-4 service__content-top_box-buttons_content-btn"
								>
									<img src={industrial} alt="icon" />
									<p>Industrial</p>
								</button>
							</div>
						</div>
					</div>
				</div>
				<div class="service__content-bottom col-12">
					<div class="service__content-bottom_content">
						<div class="row service__content-bottom_content-box">
							<div
								class="col-12 col-lg-7 col-md-6 col-sm-12 service__content-bottom_content-box_left"
							>
								<div class="service__content-bottom_content-box_left-top">
									<img src={yellowCommercial} alt="icon" />
									<p>Electrical installation</p>
								</div>
								<div class="service__content-bottom_content-box_left-center">
									<h2>Commercial</h2>
									<p>
										Electrical & Maintenance Services Ltd offers a full range of electrical services
										to suit your needs – from moving a light switch to complete house rewires.
									</p>
									<p>
										In addition to providing fully qualified, competent electricians in and around
										London, the company also runs an electrical wholesale shop.
									</p>
								</div>
								<div class="service__content-bottom_content-box_left-button">
									<button>Read More</button>
								</div>
							</div>
							<div
								class="col service__content-bottom_content-box_right"
							>
								<img src={img2} alt="img">
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<style lang="scss" scoped>
	.service {
		background: var(--yellow);
		width: 100%;
		min-height: 900px;
        position: relative;
		&__content {
			padding-top: 140px;
			&-top {
				&_box {
					display: flex;
					align-items: center;
					justify-content: center;
					flex-direction: column;
					&-top {
						display: flex;
						align-items: center;
						background: var(--light);
						padding: 0 20px;
						img {
							margin-right: 10px;
						}
						p {
							font-weight: 400;
							font-size: 18px;
							line-height: 27px;
							letter-spacing: 0.36px;
							text-transform: capitalize;
							color: var(--blue);
						}
					}
					&-center {
						margin: 20px 0 35px 0;
						display: flex;
						align-items: center;
						justify-content: center;
						flex-direction: column;
						h2 {
							font-weight: 400;
							font-size: 45px;
							line-height: 58px;
							letter-spacing: 0.36px;
							color: var(--blue);
							margin-bottom: 12px;
						}
						p {
							font-weight: 400;
							font-size: 18px;
							line-height: 27px;
							text-align: center;
							letter-spacing: 0.36px;
							color: var(--blue);
							max-width: 832px;
							width: 100%;
						}
					}
					&-buttons {
						width: 70%;
						&_content {
							display: flex;
							align-items: center;
							justify-content: center;
							&-btn {
								display: flex;
								width: 220px;
								align-items: center;
								justify-content: center;
								background: transparent;
								padding: 17px 40px;
								border: 1px solid var(--blue);
								margin: 0 15px;
								transition: 0.5s ease;
								&.active,
								&:hover {
									border: 1px solid var(--white);
									background: var(--white);
								}
								img {
									margin-right: 10px;
								}
							}
						}
					}
				}
			}
			&-bottom {
				position: absolute;
				bottom: -13%;
				left: 0;
				right: 0;
				margin: 0 auto;
				max-width: 1160px;
				width: 100%;
                background: var(--white);
                box-shadow: -1px 6px 18px rgba(0, 0, 0, 0.09);
				&_content {
					padding: 80px 60px;
					background: var(--white);
					&-box {
						&_left {
							&-top {
								display: flex;
								align-items: center;
								background: var(--light);
								padding: 0 20px;
								width: 250px;
								img {
									margin-right: 10px;
								}
								p {
									font-weight: 400;
									font-size: 17px;
									line-height: 27px;
									letter-spacing: 0.36px;
									text-transform: capitalize;
									color: var(--blue);
								}
							}
							&-center {
								display: flex;
								align-items: flex-start;
								justify-content: center;
								flex-direction: column;
								margin: 20px 0 30px 0;
								h2 {
									font-weight: 400;
									font-size: 45px;
									line-height: 58px;
									letter-spacing: 0.36px;
									color: var(--blue);
								}
								p {
									font-weight: 400;
									font-size: 18px;
									line-height: 27px;
									letter-spacing: 0.36px;
									color: var(--grey);

									&:nth-of-type(1) {
										margin: 10px 0;
									}
									&:nth-of-type(2) {
										max-width: 549px;
										width: 100%;
									}
								}
							}
							&-button {
								button {
									font-weight: 400;
									font-size: 20px;
									line-height: 30px;
									letter-spacing: 0.36px;
									color: var(--blue);
									background: var(--yellow);
									padding: 20px 42px;
								}
							}
						}
                        &_right{
                            display: flex;
                            align-items: center;
                            justify-content: center;
                            img{
                                width: 100%;
                                height: 100%;
                                pointer-events: none;
                                user-select: none;
                                touch-action: none;
                            }
                        }
					}
				}
			}
		}
	}
</style>
