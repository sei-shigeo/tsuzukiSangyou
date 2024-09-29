<footer>
	<div class="footer-container">
		<div class="footer-left">
			<img src="/logo/logo2.gif" alt="tuzuki sangyou" />
		</div>
		<div class="footer-right">
			<ul class="footer-column">
				<li class="footer-column-item">
					<a href="/"> ホーム </a>
				</li>
				<li class="footer-column-item">
					<a href="/"> 会社概要 </a>
				</li>
				<li class="footer-column-item">
					<a href="/"> 求人情報 </a>
				</li>
				<li class="footer-column-item">
					<a href="/"> お問い合わせ </a>
				</li>
			</ul>
			<ul class="footer-column">
				<li class="footer-column-item">
					<a href="/">本社営業所</a>
				</li>
				<li class="footer-column-item">
					<a href="/">二本木営業所</a>
				</li>
				<li class="footer-column-item">
					<a href="/">豊田営業所</a>
				</li>
				<li class="footer-column-item">
					<a href="/">小牧営業所</a>
				</li>
			</ul>
			<ul class="footer-column">
				<li class="footer-column-item">
					<a href="/">twitter</a>
				</li>
				<li class="footer-column-item">
					<a href="/">facebook</a>
				</li>
				<li class="footer-column-item">
					<a href="/">プライバシーポリシー</a>
				</li>
				<li class="footer-column-item">
					<a href="/">個人情報取り扱いについて</a>
				</li>
			</ul>
		</div>
	</div>
	<div class="footer-bottom">
		<small>© 2024 制作会社 Waseisyouji Co.,Ltd.(システム開発部門)</small>
	</div>
</footer>

<style>
	footer {
		width: 100%;
		background-color: rgb(175, 175, 175);
		color: var(--white);
	}
	.footer-container {
		padding: 2rem;
		padding-bottom: 0;
		display: grid;
		grid-template-columns: 1fr 1fr;
		width: 100%;
	}
	.footer-left {
		width: 100%;
		display: grid;
		place-items: center;
		& img {
			width: 500px;
			aspect-ratio: auto;
		}
	}
	.footer-right {
		width: 100%;
		padding: 2rem;
		display: flex;
		justify-content: space-between;
		align-items: center;
		& ul {
			display: grid;
			gap: 1rem;
			& li {
				list-style: disc;
				&::marker {
					color: var(--red);
				}
			}
		}
	}
	.footer-bottom {
		display: grid;
		place-items: center;
		& small {
			padding: .5rem;
		}
	}
</style>
