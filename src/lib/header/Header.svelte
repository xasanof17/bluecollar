<script>
	import facebook from './img/facebook.svg';
	import insta from './img/insta.svg';
	import twitter from './img/twitter.svg';
	import logo from './img/logo.svg';
	import pic from './img/pic.svg';
	import call from './img/call.svg';
	import mail from './img/mail.svg';
</script>

<header class="header">
	<div class="header__top">
		<div class="container">
			<div class="header__top-content">
				<div class="header__top-content_open">
					<p>Opening Hours: 06:00 to 20:00</p>
				</div>
				<div class="header__top-content_social">
					<ul class="header__top-content_social-list">
						<li class="header__top-content_social-list_item">
							<a href="#!" class="header__top-content_social-list_item-link">
								<img src={facebook} alt="facebook" />
							</a>
						</li>
						<li class="header__top-content_social-list_item">
							<a href="#!" class="header__top-content_social-list_item-link">
								<img src={twitter} alt="twitter" />
							</a>
						</li>
						<li class="header__top-content_social-list_item">
							<a href="#!" class="header__top-content_social-list_item-link">
								<img src={pic} alt="pic" />
							</a>
						</li>
						<li class="header__top-content_social-list_item">
							<a href="#!" class="header__top-content_social-list_item-link">
								<img src={insta} alt="insta" />
							</a>
						</li>
					</ul>
				</div>
			</div>
		</div>
	</div>
	<nav class="header__nav">
		<div class="container">
			<div class="header__nav-content">
				<div class="header__nav-content_top">
					<a href="#!" class="logo"><img src={logo} alt="logo" /></a>
					<div class="header__nav-content_top-about">
						<div class="header__nav-content_top-about_box">
							<div class="header__nav-content_top-about_box-img">
								<img src={mail} alt="mail" />
							</div>
							<div class="header__nav-content_top-about_box-left">
								<h4>Mail Us</h4>
								<a href="mailto:xasanof17@gmail.com">xasanof17@gmail.com</a>
							</div>
						</div>
						<div class="header__nav-content_top-about_box">
							<div class="header__nav-content_top-about_box-img">
								<img src={call} alt="call" />
							</div>
							<div class="header__nav-content_top-about_box-left">
								<h4>Call Us</h4>
								<a href="tel:+998900198505">+998 90 019 85 05</a>
							</div>
						</div>
					</div>
				</div>
				<div class="header__nav-content_bottom">
					<div class="container">
						<div class="header__nav-content_bottom-content">
							<ul class="header__nav-content_bottom-list">
								<li class="header__nav-content_bottom-list_item">
									<a href="#!" class="header__nav-content_bottom-list_item-link active">Home</a>
								</li>
								<li class="header__nav-content_bottom-list_item">
									<a href="#!" class="header__nav-content_bottom-list_item-link">About Us</a>
								</li>
								<li class="header__nav-content_bottom-list_item">
									<a href="#!" class="header__nav-content_bottom-list_item-link">Pages</a>
								</li>
								<li class="header__nav-content_bottom-list_item">
									<a href="#!" class="header__nav-content_bottom-list_item-link">Blog</a>
								</li>
								<li class="header__nav-content_bottom-list_item">
									<a href="#!" class="header__nav-content_bottom-list_item-link">Contact Us</a>
								</li>
							</ul>
							<a href="#!" class="header__nav-content_bottom-btn">Have Any Questions?</a>
						</div>
					</div>
				</div>
			</div>
		</div>
	</nav>
</header>

<style lang="scss" scoped>
	.header {
		&__top {
			background: var(--light);

			&-content {
				display: flex;
				align-items: center;
				justify-content: space-between;
				padding: 20px 0;
				flex-wrap: wrap;

				&_open {
					p {
						font-weight: 400;
						font-size: 17px;
						line-height: 27px;
						color: var(--blue);
					}
				}

				&_social {
					&-list {
						display: flex;
						&_item {
							margin: 0 10px;
						}
					}
				}
			}
		}
		&__nav {
			position: relative;
			background: var(--white);
			&-content {
				&_top {
					display: flex;
					align-items: center;
					justify-content: space-between;
					flex-wrap: wrap;
					padding: 30px 0 60px 0;
					.logo {
						img {
							pointer-events: none;
							user-select: none;
						}
					}
					&-about {
						display: flex;
						align-items: center;
						&_box {
							display: flex;
							align-items: center;
							justify-content: space-between;
							&:nth-child(1) {
								margin-right: 65px;
								@media (max-width: 575px) {
									margin-right: 0;
								}
							}
							&-img {
								width: 70px;
								height: 70px;
								display: flex;
								align-items: center;
								justify-content: center;
								margin-right: 15px;
								background: #ffb342;
								border-radius: 100px;
								img {
									width: 35px;
									height: 30px;
									pointer-events: none;
								}
							}
							&-left {
								display: flex;
								align-items: flex-start;
								justify-content: center;
								flex-direction: column;
								h4 {
									font-weight: 400;
									font-size: 20px;
									line-height: 26px;
									letter-spacing: 0.36px;
									color: var(--blue);
								}
								a {
									font-weight: 400;
									font-size: 17px;
									line-height: 27px;
									letter-spacing: 0.36px;
									color: var(--grey);
									transition: 0.5s ease;
									border-bottom: 2px solid transparent;
									padding-bottom: 2px;
									&:hover {
										border-bottom: 2px solid var(--yellow);
									}
								}
							}
						}
					}
				}
				&_bottom {
					position: absolute;
					bottom: -35%;
					left: 0;
					width: 100%;
					&-content {
						background: var(--yellow);
						display: flex;
						align-items: center;
						justify-content: space-between;
						flex-wrap: wrap;
						
						padding: 10px;
					}
					&-list {
						display: flex;
						align-items: center;
						flex-wrap: wrap;
						&_item {
							margin: 0 25px;
							&-link {
								font-weight: 400;
								font-size: 19px;
								line-height: 30px;
								letter-spacing: 0.36px;
								color: var(--dark);
								transition: 0.5s ease-in;
								&.active,
								&:hover {
									color: var(--white);
								}
							}
						}
					}
					&-btn {
						padding: 20px 42px;
						background: var(--blue);
						font-weight: 400;
						font-size: 20px;
						line-height: 30px;
						letter-spacing: 0.36px;
						color: var(--white);
					}
				}
			}
		}
	}
</style>
