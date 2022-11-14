<script>
	import { page } from '$app/stores';
</script>

<header class="header">
	<div class="container__header">
		<!-- svelte-ignore a11y-missing-content -->
		<a sveltekit:prefetch href="/" class="header__logo" id="logo"></a>
		<div class="header__line"></div>

		<nav class="header__nav">
			<div class="hamb">
				<div class="hamb__field" id="hamb">
					<span class="bar"></span>
					<span class="bar"></span>
					<span class="bar"></span>
				</div>
			</div>
			<ul class="header__list">
				<li class="header__item" class:active={$page.url.pathname === '/add-server'}>
					<a class="header__link" sveltekit:prefetch href="/add-server">Добавить сервер</a>
				</li>
				<li class="header__item">
					<!-- svelte-ignore a11y-invalid-attribute -->
					<a class="header__link" href="">Наш Discord</a>
				</li>
				<li class="header__link__login" class:active={$page.url.pathname === '/sign-in'}>
					<a sveltekit:prefetch href="/sign-in" class="header__link header__link__login__btn"><img class="header__link header__link__login__btn__arrow" src="img/arrow-header.svg" alt="">Войти</a>
				</li>
			</ul>
		</nav>
		<div class="popup">

		</div>
	</div>
</header>

<style>
	.header{
		width: 100%;
		position: absolute;
	}

	.container__header{
		max-width: 1520px;
		margin: 0 auto;
		display: flex;
		align-items: center;
		padding-top: 21px;
		padding-left: 15px;
		padding-right: 15px;
	}

	.header__logo{
		display: block;
		width: 95px;
		height: 38px;
		background-image: url(img/SUSlogo.svg);
		background-repeat: no-repeat;
	}

	.header__line{
		width: 21px;
		height: 3px;
		background-color: #fff;
		border-radius: 20px;
		transform: rotate(-90deg);
		margin-left: 60px;
		
	}

	.header__list{
		display: flex;
		list-style-type: none;
		gap: 60px;
		margin-left: 13px;
		
	}

	.header__link{
		text-decoration: none;
		color: #fff;
	}


	.header__link__login{
		position: absolute;
		right: 0;
		margin-right: 71px;
	}
	
	.header__link__login__btn{
		font-weight: bold;
	}

	.header__link__login__btn__arrow{
		position: relative;
		left: -5px;
		top: 2px;
		width: 14px;
		height: 14px;
	}

	.hamb{
		display: none;
	}

	.popup{
		display: none;
	}

	@media (max-width: 768px) {
		.header__list{
			display: none;
		}
		.header__line{
			display: none;
		}
		.hamb{
			display: flex;
			align-items: center;
			position: absolute;
			right: 0;
			top: 15px;
			
		}
		.hamb__field{
			padding: 10px 20px;
			cursor: pointer;
		}

		.bar{
			display: block;
			width: 30px;
			height: 2px;
			margin: 6px auto;
			background-color: #fff;
			transition: 0.2s;
		}
		.popup{
			position: fixed;
			top: 75px;
			left: -100%;
			width: 100%;
			height: 100%;
			background-color: #fff;
			z-index: 100;
			display: flex;
			transition: 0.3s;
		}
		/* .popup.open{
			left: 0;
		} */
	}
</style>
