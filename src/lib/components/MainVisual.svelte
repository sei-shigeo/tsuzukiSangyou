<div class="main-visual">
	<div class="main-visual-inner">
		<img class="main-visual-logo" src="/logo/logo1.gif" alt="メインビジュアル" />
		<div class="main-visual-content">
			<h1 class="main-visual-title">安全と環境を守る、未来への運送</h1>
		</div>
	</div>
</div>

<style>
	.main-visual {
		width: 100%;
		height: 100vh;
		background-image: url('/main-visual3.jpg');
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
		display: grid;
		place-items: center;
	}
	.main-visual-inner {
		width: 100%;
		padding: 2rem;
		display: grid;
		place-items: center;
		color: var(--white);
		display: grid;
		gap: 1rem;
	}
	.main-visual-logo {
		width: 1000px;
		aspect-ratio: auto;
		filter: drop-shadow(5px 5px 5px rgb(255, 255, 255));
	}
	.main-visual-title {
		font-size: 2.5rem;
		text-shadow: 0 2px 2px rgb(0, 0, 0);
	}
</style>
