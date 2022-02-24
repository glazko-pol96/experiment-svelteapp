<script>
	export let name;
</script>

<main>
	<div class="elem-animate" id="elem1" />
	<div class="elem-animate" id="elem2" />
	<div class="elem-animate" id="elem3" />
	<div class="elem-animate" id="elem4" />
	<div class="elem-animate" id="elem5" />
	<div class="elem-animate" id="elem6" />
	<div class="elem-animate" id="elem7" />
	<div class="elem-animate" id="elem8" />
	<div class="elem-animate" id="elem9" />
	<div class="elem-animate" id="elem10" />
</main>

<style>
	main {
	  display: flex;
  	justify-content: space-between;
	}

	.elem-animate {
		width: 100px;
		height: 100px;
		border-radius: 50%;
		margin: 15px;
		box-shadow: 8px 8px 8px 4px rgba(0, 0, 0, 0.2);
		animation-name: animate-up-down;
		animation-timing-function: ease-in;
		animation-iteration-count: infinite;
		animation-direction: alternate-reverse;
	}

	#elem1 {
		background: linear-gradient(70deg, #FF891D, #FFF61D);
		animation-duration: 2s;
	}

	#elem2 {
		background: linear-gradient(#FF891D, #FFF61D);
		animation-duration: 3s;
	}

	#elem3 {
		background: linear-gradient(to bottom left, #FF891D, #FFF61D);
		animation-duration: 4s;
	}

	#elem4 {
		background: linear-gradient(#FF891D, #FFF61D, #FF891D, #FFF61D);
		animation-duration: 2s;
	}

	#elem5 {
		background: linear-gradient(#FFF61D, #FF891D, #FFF61D, #FF891D);
		animation-duration: 3s;
	}

	#elem6 {
		background: linear-gradient(to right, #FFF61D, #FF891D, #FFF61D, #FF891D);
		animation-duration: 4s;
	}

	#elem7 {
		background: linear-gradient(to left, #FFF61D, #FF891D, #FFF61D, #FF891D);
		animation-duration: 2s;
	}

	#elem8 {
		background: linear-gradient(#FF891D, #FF480E);
		animation-duration: 3s;
	}

	#elem9 {
		background: linear-gradient(70deg, #FF891D, #FF480E);
		animation-duration: 2s;
	}

	#elem10 {
		background: linear-gradient(to left, #FF891D, #FF480E, #FF891D, #FF480E);
		animation-duration: 3s;
	}

	@keyframes animate-up-down {
		from {
			margin-top: 0;
		}
		to {
			margin-top: 80vh;
		}
	}
</style>