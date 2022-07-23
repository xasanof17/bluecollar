<script>
	import edit from './img/edit.svg';
	import next from './img/next.svg';
	import prev from './img/prev.svg';
	import girl from './img/girl.svg';
	import quotation from './img/quotation.svg';
</script>

<section class="contact">
	<div class="container">
		<div class="contact__content">
			<div class="row">
				<div class="col-12 col-lg-6">
					<div class="testimonial">
						<div class="testimonial__top">
							<img src={edit} alt="img" />
							<p>Testimonial</p>
						</div>
						<h2>Customers Says</h2>
						<div class="testimonial__card">
							<div class="testimonial__card-top">
								<div class="testimonial__card-top_user">
									<img src={girl} alt="img" />
									<div class="testimonial__card-top_user-about">
										<h4>Nancy luther</h4>
										<span>NewYork</span>
									</div>
								</div>
								<div class="testimonial__card-top_img">
									<img src={quotation} alt="queatetion" />
								</div>
							</div>
							<div class="testimonial__card-center">
								<p>
									We have had several good experiences with <strong>Blue Collar</strong> team. Most
									recently, they replaced our 20-year-old HVAC system with a new,
									<strong> modern, and more efficient</strong> system & it worked fine.
								</p>
							</div>
							<div class="testimonial__card-bottom">
								<button class="next"><img src={prev} alt="next" /></button>
								<button class="prev"><img src={next} alt="prev" /></button>
							</div>
						</div>
					</div>
				</div>
				<div class="col-12 col-lg-6" />
			</div>
		</div>
	</div>
</section>

<style lang="scss" scoped>
	.contact {
		background: var(--white);
		&__content {
			padding: 150px 0 120px 0;
			.testimonial {
				&__top {
					display: flex;
					align-items: center;
					background: var(--light);
					padding: 20px 0;
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
				h2 {
					font-weight: 400;
					font-size: 45px;
					line-height: 58px;
					letter-spacing: 0.36px;
					color: var(--blue);
				}
				&__card {
					background: var(--white);
					padding: 40px;
					border: 1px solid #dddddd;
					&-top {
						display: flex;
						align-items: center;
						justify-content: space-between;
						padding-bottom: 30px;
						border-bottom: 1px solid #dcdcdc;
						&_user {
							display: flex;
							align-items: center;
							justify-content: center;
							img {
								margin-right: 10px;
							}
							&-about {
								display: flex;
								align-items: flex-start;
								justify-content: center;
								flex-direction: column;
								h4 {
									font-weight: 400;
									font-size: 22px;
									line-height: 31px;
									letter-spacing: 0.36px;
									color: var(--blue);
								}
								span {
									font-weight: 400;
									font-size: 18px;
									line-height: 27px;
									letter-spacing: 0.36px;
									color: var(--grey);
								}
							}
						}
						&_img {
							padding: 15px;
							border-radius: 50%;
							background: var(--yellow);
							img {
								pointer-events: none;
								user-select: none;
							}
						}
					}
					&-center {
						margin: 20px 0;
						p {
							font-weight: 700;
							font-size: 18px;
							line-height: 27px;
							letter-spacing: 0.36px;
							color: var(--grey);
							max-width: 509px;
							width: 100%;
							strong {
								font-weight: bold;
								color: var(--blue);
							}
						}
					}
					&-bottom {
						display: flex;
						align-items: center;
						button {
							width: 50px;
							height: 50px;
							background: var(--light);
							border-radius: 50%;
							display: flex;
							align-items: center;
							justify-content: center;
						}
						.next {
							margin-right: 20px;
						}
					}
				}
			}
		}
	}
</style>
