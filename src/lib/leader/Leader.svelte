<script>
	import setting from './img/settingicon.svg';
</script>

<section class="home">
	<div class="container">
		<div class="home__content">
			<div class="row">
				<div class="col-12 col-lg-8 home__content-box">
					<div class="home__content-box_top">
						<img src={setting} alt="settingicon" />
						<p>Improve our customers’ lives by providing effective solutions.</p>
					</div>
					<div class="home__content-box_center">
						<h1>A recognized leader in services industry</h1>
					</div>
					<div class="home__content-box_bottom">
						<a href="#!">View Services</a>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<style lang="scss" scoped>
	.home {
		background: url('../../assets/imgs/header.svg') no-repeat center / cover;
		min-height: 740px;
		display: flex;
		align-items: center;
		justify-content: flex-start;
		&__content {
			&-box {
				&_top {
					display: flex;
					align-items: center;
					background: var(--shadow);
					max-width: 660px;
					width: 100%;
					padding-left: 20px;
					padding-right: 40px;
					img {
						padding-right: 10px;
					}
					p {
						font-weight: 400;
						font-size: 18px;
						line-height: 27px;
						letter-spacing: 0.36px;
						text-transform: capitalize;
						color: var(--white);
					}
				}
				&_center {
					margin: 30px 0;
					h1 {
						font-weight: 400;
						font-size: 60px;
						line-height: 78px;
						letter-spacing: 1.2px;
						text-transform: capitalize;
						color: var(--white);
					}
				}
				&_bottom {
					position: relative;
					z-index: 2;
					a {
						font-weight: 400;
						font-size: 20px;
						line-height: 30px;
						letter-spacing: 0.36px;
						color: var(--blue);
						padding: 20px 42px;
						background: var(--yellow);
						position: relative;
						z-index: 2;
						&::before {
							content: '';
							position: absolute;
							top: 0;
							left: 0;
							width: 0;
							height: 100%;
							background: var(--white);
							transition: 0.5s;
							z-index: -1;
						}
						&:hover {
							color: var(--blue);
							&::before {
								width: 100%;
							}
						}
					}
				}
			}
		}
	}
</style>
