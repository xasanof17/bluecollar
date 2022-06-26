<script>
	import img1 from './img/img1.svg';
	import icon from './img/main-icon.svg';
</script>

<section class="provide">
	<div class="container">
		<div class="provide__content">
			<div class="row">
				<div class="col-12 col-lg-6 col-md-12 col-sm-12 provide__left">
					<img src={img1} alt="img1" class="provide__left-img" />
				</div>
				<div class="col-12 col-lg-6 col-md-12 col-sm-12 provide__right">
					<div class="provide__right-top">
						<img src={icon} alt="icon" />
						<p>Welcome BlueCollar</p>
					</div>
					<div class="provide__right-center">
						<h2>We Provide Your Future</h2>
						<p>
							Bluecollar Electrical services was established in 2008. We are trusted and reliable
							electricians who serve customers in the city as well as throughout United States Of
							America.
						</p>
						<p>
							We have extensive experience of domestic and business electrical installations and no
							job is too small. Our customers value our professionalism, work ethic and our
							competitive prices.
						</p>
					</div>
					<div class="provide__right-bottom">
						<div class="row">
							<div class="col-12 col-lg-4 col-md-6 provide__right-bottom-left">
								<div class="provide__right-bottom-left_box">
									<span>35</span>
									<p>Years Of Experience</p>
								</div>
							</div>
							<div class="col provide__right-bottom-right">
								<div class="provide__right-bottom-right_box">
									<ul>
										<li>- For all your system requirements</li>
										<li>- All work undertaken by qualified</li>
										<li>- Experienced office staff on hand</li>
										<li>- A Full Guarantee On Workmanship</li>
										<li>- Properties at a reasonable price.</li>
									</ul>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<style lang="scss">
	.provide {
		padding: 140px 0;
		&__content {
			.provide__left {
                height: 580px;
				&-img {
					width: 100%;
                    height: 100%;
					pointer-events: none;
					user-select: none;
					touch-action: none;
				}
			}
			.provide__right {
                padding: 20px 0 0 38px;
				&-top {
					display: flex;
					align-items: center;
					padding: 0 20px;
					background: var(--light);
					max-width: 250px;
					width: 100%;
					img {
						margin-right: 10px;
						pointer-events: none;
						user-select: none;
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
					margin: 20px 0;
					h2 {
						font-weight: 400;
						font-size: 45px;
						line-height: 58px;
						letter-spacing: 0.36px;
						color: #1c2752;
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
							max-width: 552px;
							width: 100%;
						}
					}
				}
				&-bottom {
					&-left {
						&_box {
							display: flex;
							align-items: center;
							justify-content: center;
							flex-direction: column;
							background: var(--light);
							padding: 40px;
							span {
								font-weight: 400;
								font-size: 80px;
								line-height: 88px;
								text-align: center;
								letter-spacing: 0.36px;
								color: var(--yellow);
								margin-bottom: 15px;
							}
							p {
								font-weight: 400;
								font-size: 20px;
								line-height: 26px;
								text-align: center;
								letter-spacing: 0.36px;
								color: var(--blue);
								max-width: 112px;
								width: 100%;
							}
						}
					}
					&-right {
						display: flex;
						align-items: center;
						justify-content: center;
						&_box {
							ul {
								li {
									font-weight: 400;
									font-size: 20px;
									line-height: 27px;
									letter-spacing: 0.36px;
                                    color: var(--grey);
                                    margin: 7px 0;
								}
							}
						}
					}
				}
			}
		}
	}
</style>
