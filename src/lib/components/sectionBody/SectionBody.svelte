<script>
	export let key;
</script>

{#if key === 'about'}
	<div class={`${key}-content`}>
		<p>
			愛知県県安城市にある都築産業は、自動車部品を主に輸送・物流業務を行っております。愛知県から東北、関東、関西など近距離から長距離まで安全な管理・配送を心掛けています。
		</p>
		<p>
			近年の運送・物流業界では、運送サービスの需要が高まっていること、人手不足、ドライバーの高齢化などが問題として挙げられていますが、お客様の頼れるパートナーとしていただけるよう、日々業務に取り組んでいます。
		</p>
		<a href="/about" class="about-more">詳細を見る</a>
	</div>
{:else if key === 'company'}
	<div class={`${key}-content`}>
		<ul class="card-list">
			<li class="card-item-list">
				<a class="card-item" href="/company">
					<h3 class="card-title">会社方針</h3>
					<p class="card-text">
						Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quos. Lorem ipsum
						dolor sit amet consectetur adipisicing elit. Quisquam, quos. Lorem ipsum dolor sit amet
						consectetur adipisicing elit. Quisquam, quos.
					</p>
					<a href="/company" class="card-more">詳細を見る</a>
				</a>
			</li>
			<li class="card-item-list">
				<a class="card-item" href="/company">
					<h3 class="card-title">会社沿革</h3>
					<p class="card-text">
						Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quos.
					</p>
					<a href="/company" class="card-more">詳細を見る</a>
				</a>
			</li>
			<li class="card-item-list">
				<a class="card-item" href="/company">
					<h3 class="card-title">経営理念</h3>
					<p class="card-text">
						Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quos.
					</p>
					<a href="/company" class="card-more">詳細を見る</a>
				</a>
			</li>
		</ul>
	</div>
{:else if key === 'service'}
	<div class={`${key}-content`}>
		<ul class="service-list">
			<li class="service-item-list">
				<a class="service-item" href="/service">
					<span class="service-item-title">定期便</span>
					<span class="service-item-more">詳細を見る</span>
				</a>
			</li>
			<li class="service-item-list">
				<a class="service-item" href="/service">
					<span class="service-item-title">スポット便</span>
					<span class="service-item-more">詳細を見る</span>
				</a>
			</li>
			<li class="service-item-list">
				<a class="service-item" href="/service">
					<span class="service-item-title">サービス1</span>
					<span class="service-item-more">詳細を見る</span>
				</a>
			</li>
		</ul>
	</div>
{:else if key === 'recruit'}
	<div class={`${key}-content`}>
		<a class="recruit-link" href="/company">
			<h3 class="recruit-title">ドライバー＆管理者 募集中</h3>
			<ul class="recruit-list">
				<li class="recruit-item">
					(定期便) 中型トラックの運転手を募集しています。<br />
				</li>
				<li class="recruit-item">
					(定期便) 大型トラックの運転手を募集しています。<br />
				</li>
				<li class="recruit-item">
					運行管理者、整備管理者を募集しています。<br />
				</li>
			</ul>
			<span class="recruit-more">詳細を見る</span>
		</a>
	</div>
{:else if key === 'branch'}
	<div class={`${key}-content`}>
		<ul class="branch-list">
			<li class="branch-item">
				<a class="branch-link" href="/branch" style="background-image: url('/mainoffice.png');">
					<h3 class="branch-title">本社</h3>
					<dl class="branch-info">
						<div class="branch-info-item address">
							<dt>住所：</dt>
							<dd>〒446-0051<br />愛知県安城市箕輪町東山85番地5</dd>
						</div>
						<div class="branch-info-item">
							<dt>電話：</dt>
							<dd>0566-74-1119</dd>
						</div>
						<div class="branch-info-item">
							<dt>FAX：</dt>
							<dd>0566-74-6966</dd>
						</div>
						<div class="branch-info-item">
							<dt>営業時間：</dt>
							<dd>9:00-18:00</dd>
						</div>
					</dl>
					<span class="branch-more">詳細を見る</span>
				</a>
			</li>
			<li class="branch-item">
				<a class="branch-link" href="/branch" style="background-image: url('/nihongioffice.png');">
					<h3 class="branch-title">二本木営業所</h3>
					<dl class="branch-info">
						<div class="branch-info-item address">
							<dt>住所：</dt>
							<dd>〒446-0075<br />愛知県安城市二本木新町北菅口31-1</dd>
						</div>
						<div class="branch-info-item">
							<dt>電話：</dt>
							<dd>0566-75-0003</dd>
						</div>
						<div class="branch-info-item">
							<dt>FAX：</dt>
							<dd>0566-75-0012</dd>
						</div>
						<div class="branch-info-item">
							<dt>営業時間：</dt>
							<dd>9:00-18:00</dd>
						</div>
					</dl>
					<span class="branch-more">詳細を見る</span>
				</a>
			</li>
			<li class="branch-item">
				<a class="branch-link" href="/branch" style="background-image: url('/toyotaoffice.png');">
					<h3 class="branch-title">豊田営業所</h3>
					<dl class="branch-info">
						<div class="branch-info-item address">
							<dt>住所：</dt>
							<dd>〒473-0911<br />愛知県豊田市本町石根134-1</dd>
						</div>
						<div class="branch-info-item">
							<dt>電話：</dt>
							<dd>0565-42-8177</dd>
						</div>
						<div class="branch-info-item">
							<dt>FAX：</dt>
							<dd>0566-42-8122</dd>
						</div>
						<div class="branch-info-item">
							<dt>営業時間：</dt>
							<dd>9:00-18:00</dd>
						</div>
					</dl>
					<span class="branch-more">詳細を見る</span>
				</a>
			</li>
			<li class="branch-item">
				<a class="branch-link" href="/branch" style="background-image: url('/mainoffice.png');">
					<h3 class="branch-title">小牧支店</h3>
					<dl class="branch-info">
						<div class="branch-info-item address">
							<dt>住所：</dt>
							<dd>〒473-0911<br />愛知県小牧市xxxxxxxxxxxxxxxxx</dd>
						</div>
						<div class="branch-info-item">
							<dt>電話：</dt>
							<dd>0565-42-8177</dd>
						</div>
						<div class="branch-info-item">
							<dt>FAX：</dt>
							<dd>0566-42-8122</dd>
						</div>
						<div class="branch-info-item">
							<dt>営業時間：</dt>
							<dd>9:00-18:00</dd>
						</div>
					</dl>
					<span class="branch-more">詳細を見る</span>
				</a>
			</li>
		</ul>
	</div>
{:else if key === 'contact'}
	<div class={`${key}-content`}>
		<a class="contact-link" href="/company">
			<h3 class="contact-title">お問い合わせはこちら</h3>
		</a>
	</div>
{:else}
	<div class={`${key}-content`}>

	</div>
{/if}

<style>
	.about-content {
		width: 50%;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		gap: 20px;
		text-align: center;
	}
	.about-more {
		margin-top: 50px;
		display: inline-block;
		padding: 10px 20px;
		background-color: #007bff;
		color: #fff;
		text-decoration: none;
		border-radius: 5px;
		transition: background-color 0.3s;
	}
	.company-content {
		width: 100%;
	}
	.card-list {
		width: 100%;
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
		justify-content: center;
		align-items: center;
		gap: 20px;
	}
	.card-item-list {
		display: grid;
		grid-template-rows: subgrid;
	}
	.card-item {
		position: relative;
		padding: 20px;
		background-image: url('https://picsum.photos/200/300');
		background-size: cover;
		background-position: center;
		width: 100%;
		display: grid;
		grid-template-rows: auto 1fr auto;
		gap: 20px;
		color: #fff;
		filter: brightness(0.9);
		box-shadow: 6px 6px 6px rgba(0, 0, 0, 0.5);
		transition: all 0.3s;
		&:hover {
			transform: translateY(-10px);
			filter: brightness(1.1);
		}
	}
	.card-title {
		font-size: 20px;
		font-weight: bold;
		border-bottom: 1px solid #fff;
		padding: 6px 0;
		/* background-color: red; */
	}
	.card-text {
		font-size: 16px;
		font-weight: normal;
		/* background-color: green; */
	}
	.card-more {
		font-size: 16px;
		font-weight: normal;
		width: fit-content;
		padding: 10px 20px;
		border-radius: 5px;
		text-decoration: none;
		background-color: #007bff;
		color: #fff;
	}
	.service-content {
		width: 100%;
	}
	.service-list {
		width: 100%;
		display: flex;
		justify-content: center;
		align-items: center;
		gap: 50px;
		/* background: linear-gradient(to top, var(--primary) 5%, #fff 30%); */
	}
	.service-item {
		width: 200px;
		height: 200px;
		border-radius: 50%;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		gap: 20px;
		background-image: url('https://picsum.photos/200/300');
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
		box-shadow: 6px 6px 10px rgba(0, 0, 0, 0.5);
		filter: brightness(0.9);
		transition: all 0.3s;
		&:hover {
			transform: translateY(-10px);
			filter: brightness(1.1);
			box-shadow: 6px 6px 10px rgba(0, 0, 0, 0);
		}
		& .service-item-title {
			font-size: 20px;
			font-weight: bold;
			color: #fff;
		}
		& .service-item-more {
			font-size: 16px;
			font-weight: normal;
			width: fit-content;
			padding: 10px 20px;
			border-radius: 5px;
			text-decoration: none;
			background-color: #007bff;
			color: #fff;
		}
	}
	.recruit-content {
		width: 100%;
		display: grid;
		place-items: center;
	}
	.recruit-link {
		width: 50%;
		height: 100%;
		padding: 20px;
		display: grid;
		gap: 20px;
		border-radius: 10px;
		backdrop-filter: blur(10px);
		box-shadow: 6px 6px 10px rgba(0, 0, 0, 0.5);
	}
	.recruit-title {
		font-size: 2rem;
		font-weight: bold;
	}
	.recruit-list {
		width: 100%;
		display: flex;
		flex-direction: column;
		gap: 10px;
	}
	.recruit-item {
		padding: 10px;
		list-style: disc;
		font-size: 16px;
		font-weight: normal;
		list-style-position: inside;
	}
	.recruit-more {
		font-size: 16px;
		font-weight: normal;
		padding: 10px 20px;
		border-radius: 5px;
		text-decoration: none;
		background-color: #007bff;
		color: #fff;
		text-align: center;
		box-shadow: 6px 6px 10px rgba(0, 0, 0, 0.5);
		transition: all 0.3s;
		&:hover {
			transform: translateY(10px);
			box-shadow: 6px 6px 10px rgba(0, 0, 0, 0);
		}
	}
	.branch-content {
		width: 100%;
	}
	.branch-list {
		width: 100%;
		display: flex;
		gap: 20px;
	}
	.branch-item {
		width: 100%;
		display: flex;
	}
	.branch-link {
		width: 100%;
		padding: 1rem;
		display: grid;
		grid-template-rows: subgrid;
		gap: 20px;
		background-color: green;
		background-image: url('/mainoffice.png');
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
		filter: brightness(0.9);
		box-shadow: 6px 6px 6px rgba(0, 0, 0, 0.5);
		transition: all 0.3s;
		color: #fff;
		text-shadow: 2px 2px 1px rgba(0, 0, 0, 1);
		&:hover {
			transform: translateY(-10px);
			filter: brightness(1.1);
		}
	}
	.branch-info {
		width: 100%;
		display: grid;
		gap: 10px;
	}
	.branch-info-item {
		display: grid;
	}
	.branch-info-item dt {
		font-weight: bold;
	}
	.branch-info-item dd {
		font-weight: normal;
	}
	.branch-more {
		width: fit-content;
		font-size: 16px;
		font-weight: normal;
		padding: 10px 20px;
		border-radius: 5px;
		text-decoration: none;
		background-color: #007bff;
		color: #fff;
		text-align: center;
		text-shadow: none;
	}
	.contact-content {
		width: 100%;
	}
	.contact-link {
		width: 50%;
		height: 20vh;
		margin: 0 auto;
		display: grid;
		place-items: center;
		background-color: hsla(211, 100%, 50%, 0.8);
		color: var(--white);
		text-decoration: none;
		border-radius: 10px;
		box-shadow: 6px 6px 10px rgba(0, 0, 0, 0.5);
		transition: all 0.3s;
		&:hover {
			transform: translateY(10px);
		}
	}
	.contact-title {
		font-size: 2rem;
		font-weight: bold;
	}
</style>
