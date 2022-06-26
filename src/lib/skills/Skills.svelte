<script>
    import edit from './img/edit.svg';
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
                    <div class="col-12 col-lg-4 col-md-6 skills__content-cards_block-card">axax</div>
                    <div class="col-12 col-lg-4 col-md-6 skills__content-cards_block-card">axax</div>
                    <div class="col-12 col-lg-4 col-md-6 skills__content-cards_block-card">axax</div>
                    <div class="col-12 col-lg-4 col-md-6 skills__content-cards_block-card">axax</div>
                    <div class="col-12 col-lg-4 col-md-6 skills__content-cards_block-card">axax</div>
                    <div class="col-12 col-lg-4 col-md-6 skills__content-cards_block-card">axax</div>
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
			}
		}
	}
</style>
