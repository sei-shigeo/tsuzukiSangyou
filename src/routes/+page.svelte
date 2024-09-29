<script>
	import SectionBody from '$lib/components/sectionBody/SectionBody.svelte';
	let section = {
		about: {
			title: 'About',
			subtitle: '当社について',
			image: ''
		},
		company: {
			title: 'Company',
			subtitle: '会社案内',
			image: '/company1.jpg'
		},
		service: {
			title: 'Service',
			subtitle: '事業内容',
			image: ''
		},
		recruit: {
			title: 'Recruit',
			subtitle: '採用情報',
			image: '/recruit1.jpg'
		},
		branch: {
			title: 'Branch',
			subtitle: '拠点一覧',
			image: '/branch1.jpg'
		},
		contact: {
			title: 'Contact',
			subtitle: 'お問い合わせ',
			image: '/contact1.jpg'
		}
	};
</script>

<div class="main-container">
	{#each Object.entries(section) as [key, value]}
		<section
			id={key}
			style={value.image
				? `background-image: url(${value.image});`
				: `background: linear-gradient(to top, var(--primary) 5%, #fff 30%);`}
		>
			<div class="container">
				<div class="section-heading">
					<h2 class="section-title">{value.title}</h2>
					<span class="section-subtitle">{value.subtitle}</span>
				</div>
				<div class="section-body">
					<SectionBody {key} />
				</div>
			</div>
		</section>
	{/each}
</div>

<style>
	section {
		width: 100%;
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
		padding: 2rem;
	}
	.container {
		width: min(100%, 1600px);
		margin: 0 auto;
		padding: 1rem;
		background-color: rgba(255, 255, 255, 0.5);
		display: grid;
		grid-template-rows: auto 1fr;
		gap: 1rem;
	}
	.section-title {
		font-size: 5rem;
		font-weight: 900;
		color: var(--primary);
		border-bottom: 1px solid var(--primary);
		text-shadow: 10px 5px 5px rgba(0, 0, 0, 0.5);
		font-style: italic;
	}
	.section-title::first-letter {
		color: var(--accent);
	}
	.section-subtitle {
		font-size: 2rem;
		font-weight: 900;
		color: var(--primary);
		text-shadow: 10px 5px 5px rgba(0, 0, 0, 0.5);
		font-style: italic;
	}
	.section-body {
		padding: 1rem;
		display: grid;
		place-items: center;
	}
</style>
