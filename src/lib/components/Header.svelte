<div class="header-inner">
	<div class="header-logo">
		<a href="/">
			<img src="/logo/logo1.gif" alt="" />
		</a>
	</div>
	<!-- navigation -->
	<nav class="header-nav">
		<ul class="header-nav-list">
			<li class="header-nav-item">
				<a href="#company">会社案内</a>
			</li>
			<li class="header-nav-item">
				<a href="#service">事業内容</a>
			</li>
			<li class="header-nav-item">
				<a href="#recruit">採用情報</a>
			</li>
			<li class="header-nav-item">
				<a href="#branch">拠点一覧</a>
			</li>
			<li class="header-nav-item">
				<a href="#contact">お問い合わせ</a>
			</li>
		</ul>
	</nav>
</div>

<style>
	.header-inner {
		width: min(100%, 1600px);
		margin: 0 auto;
		padding: 1rem;
		display: flex;
		justify-content: space-between;
		align-items: center;
		color: var(--black);
		background-color: var(--white);
	}
	.header-logo {
		& img {
			width: 300px;
		}
		& a {
			display: grid;
		}
	}

	.header-nav-list {
		display: flex;
		gap: 1.5rem;
		align-items: center;
	}
	.header-nav-item {
		&:last-child a {
			border-right: 1px solid var(--black);
			padding-right: 1rem;
		}
		& a {
			font-weight: 900;
			border-left: 1px solid var(--black);
			padding-left: 1rem;
			&:hover {
				color: var(--primary);
			}
		}
	}
</style>
