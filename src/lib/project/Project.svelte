<script>
	import edit from './img/edit.svg';
    import checked from './img/checked-icon.svg';
</script>

<section class="project">
	<div class="container">
		<div class="project__content">
			<div class="row project__content-boxs">
				<div class="col-12 col-lg-6 col-md-6 project__content-boxs_left">
					<div class="project__content-boxs_left-inner">
						<div class="project__content-boxs_left-inner_box">
							<div class="left">3956</div>
							<div class="right">Project Done</div>
						</div>
						<div class="project__content-boxs_left-inner_box">
							<div class="left">854</div>
							<div class="right">People Working</div>
						</div>
						<div class="project__content-boxs_left-inner_box">
							<div class="left">265</div>
							<div class="right">Business Partners</div>
						</div>
						<div class="project__content-boxs_left-inner_box">
							<div class="left">845+</div>
							<div class="right">Happy Customers</div>
						</div>
					</div>
				</div>
				<div class="col-12 col-lg-6 col-md-6 project__content-boxs_right">
					<div class="project__content-boxs_right-inner">
						<div class="project__content-boxs_right-inner_top">
							<img src={edit} alt="img" />
							<p>Why Choose Us</p>
						</div>
						<div class="project__content-boxs_right-inner_center">
							<h2>Few Reasons Why You Should Choose Us</h2>
							<p>
								We are offering the following information's about us that what we actually do in the
								electrical sector. To Improve our customers’ lives by providing creative and
								cost-effective solutions to their needs.
							</p>
						</div>
						<div class="project__content-boxs_right-inner_bottom">
							<div class="project__content-boxs_right-inner_bottom-box">
								<div class="left">
									<img src={checked} alt="" />
								</div>
								<div class="right">
									<h4>35 Years Experience</h4>
									<p>
										Effective communication is the key to success for any business. From our office
										staff, to our field.
									</p>
								</div>
							</div>
							<div class="project__content-boxs_right-inner_bottom-box">
								<div class="left">
									<img src={checked} alt="" />
								</div>
								<div class="right">
									<h4>Excellence Certificate</h4>
									<p>
										We understand fully that your time is of extreme value. We are committed to
										meeting deadlines.
									</p>
								</div>
							</div>
							<div class="project__content-boxs_right-inner_bottom-box">
								<div class="left">
									<img src={checked} alt="" />
								</div>
								<div class="right">
									<h4>Affordable Price</h4>
									<p>
										We adhere strictly to the current National Electrical Code, and we conduct
										regular in-house sessions.
									</p>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<style lang="scss" scoped>
	.project {
		&__content {
			&-boxs {
				display: flex;
				&_left {
					background: url('./img/header.svg');
					background-repeat: no-repeat;
					background-position: center;
					padding: 120px 80px;
					&-inner {
						padding: 100px 80px 140px 80px;
						background: var(--lightBlue);
						&_box {
							max-width: 400px;
							width: 100%;
							margin: 12px 0;
							display: flex;
							height: 67px;
							.left {
								background: var(--yellow);
								display: flex;
								align-items: center;
								justify-content: center;
								font-weight: 400;
								font-size: 24px;
								line-height: 35px;
								letter-spacing: 0.36px;
								color: var(--blue);
								width: 110px;
							}
							.right {
								padding: 16px 0 16px 20px;
								background: transparent;
								font-weight: 400;
								font-size: 25px;
								line-height: 35px;
								letter-spacing: 0.36px;
								color: var(--white);
								border: 1px solid var(--white);
								width: 100%;
							}
						}
					}
				}
				&_right {
                    padding: 100px 80px;
                    background: var(--white);
					&-inner {
						&_top {
							padding: 0 20px;
							background: var(--light);
							display: flex;
							align-items: center;
                            width: 213px;
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
						&_center {
                            margin: 23px 0 37px 0;
							h2 {
								font-weight: 400;
								font-size: 45px;
								line-height: 58px;
								letter-spacing: 0.36px;
								color: var(--blue);
								margin-bottom: 10px;
							}
							p {
								font-weight: 400;
								font-size: 17px;
								line-height: 27px;
								letter-spacing: 0.36px;
								color: var(--grey);
							}
						}
						&_bottom {
							&-box {
								display: flex;
								align-items: flex-start;
                                margin: 10px 0;
								.left {
                                    margin-right: 20px;
									img {
										pointer-events: none;
									}
								}
								.right {
									h4 {
										font-weight: 400;
										font-size: 20px;
										line-height: 28px;
										letter-spacing: 0.36px;
										color: var(--blue);
										margin-bottom: 8px;
									}
									p {
										font-weight: 400;
										font-size: 17px;
										line-height: 27px;
										letter-spacing: 0.36px;
										color: var(--grey);
                                        max-width: 432px;
                                        width: 100%;
									}
								}
							}
						}
					}
				}
			}
		}
	}
</style>
