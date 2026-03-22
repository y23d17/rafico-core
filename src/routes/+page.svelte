<script>
	import Rafico from '@/lib/assets/images/rafico.png';
	import Bubbles from '@/lib/assets/images/bubbles.png';
	import Corals from '@/lib/assets/images/corals.png';
</script>

<main class="responsive no-padding">
	<div id="rfc-hero-banner" class="center-align">
		<nav>
			<button class="circle transparent large">
				<i class="rfc-action-icon">account_circle</i>
			</button>

			<div class="max"></div>

			<button class="circle transparent large">
				<i class="rfc-action-icon">settings</i>
			</button>
		</nav>

		<div>
			<h3>Hi there!</h3>
			<div class="padding">
				<img src={Rafico} alt="rafico" width="256" />
			</div>
			<h1 id="rfc-title">Rafico</h1>
		</div>

		<img id="rfc-hero-banner-bg" src={Bubbles} alt="bubbles" />
	</div>

	<div id="rfc-menu-container" class="center-align">
		<div id="rfc-menu" class="padding grid">
			<button class="primary-container s12 m4 large round rfc-menu-btn">Journals</button>
			<button class="primary-container s12 m4 large round rfc-menu-btn">Chat</button>
			<button class="primary-container s12 m4 large round rfc-menu-btn">Music</button>
		</div>

		<img id="rfc-menu-bg" src={Corals} alt="corals" />
	</div>
</main>

<style type="text/css">
	main {
		height: 100vh;
		background-color: #fef0e1;
	}
	h1 {
		font-family: MoreSugar Regular;
	}

	h3 {
		font-family: Raleway SemiBold;
	}

	#rfc-hero-banner {
		border-radius: 0 0 2rem 2rem;
		clip-path: fill-box;
	}

	#rfc-title {
		color: #c39fd7;
	}

	#rfc-menu-container {
		position: relative;
		height: 100%;
	}

	#rfc-menu {
		position: sticky;
		z-index: 1;
	}

	#rfc-hero-banner-bg {
		width: 100%;
		height: auto;
		position: absolute;
		z-index: 0;
		top: 0;
		left: 0;
		right: 0;
		bottom: 0;
	}

	#rfc-menu-bg {
		width: 100%;
		height: auto;
		position: sticky;
		z-index: 0;
		top: 0;
		bottom: 0;
	}

	.rfc-action-icon {
		font-size: 2.5rem;
		width: auto;
		height: auto;
	}

	.rfc-menu-btn {
		font-size: 2rem;
		font-family: Raleway Bold;
		padding: 1rem;
	}

	#rfc-hero-banner,
	.rfc-menu-btn {
		background-image: linear-gradient(to right, #5de0e6, #004aad);
	}

	.rfc-menu-btn:active,
	.rfc-menu-btn:hover {
		background-color: #ffffff;
	}
</style>
