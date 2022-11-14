<script>
	export const prerender = true;
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="main">
	<div class="container">
		<div class="content">
			<div class="content__image">
				<img class="content__img" src="img/img-mine.png" alt="">
			</div>
			<div class="content__text">
				<h1 class="content__title">USER SCORE</h1>
				<p class="content__slowtext">Сервис оценки игровых серверов, прям как metacritic
					<br>И доступен прямо в Discord!</p>
				<!-- svelte-ignore a11y-invalid-attribute -->
				<a class="content__button" href=""><img class="content__button__img" src="img/discord.svg" alt="">Подключится</a>
			</div>
		</div>
		<div class="scrol">
			<img class="scrol__img" src="img/scroll.svg" alt="">
		</div>
	</div>
</section>

<section class="features">
	<div class="container">
		<h2 class="features__title">Тут можно найти
		<br><span class="features__title__color">Любой</span> сервер</h2>
		<div class="content__features">
			<div class="content__features__image">
				<img class="content__features__img" src="img/globus.svg" alt="">
			</div>
			<div class="content__features__text">
				<div class="features__item">
					<img src="img/eclips1.svg" alt="" class="features__item-img">
					<h4 class="features__item-title">Только актуальные</h4>
					<p class="features__item-text">Все сервера в SUS проходят проверку на<br>
						актуальность. В отличии от остальных<br>
						рейтингов,  SUS содержит только<br>
						самые релевантные сервера сообщества.</p>
				</div>
				<div class="features__item">
					<img src="img/eclips2.svg" alt="" class="features__item-img">
					<h4 class="features__item-title">Сервера на любой вкус</h4>
					<p class="features__item-text">В SUS может попасть любой сервер. Тут<br>
						есть РП сервера, РПГ проекты, PVP, PVE,<br>
						и даже PVPVE! Удобный список не даст<br>
						запутаться во всем разнообразии.</p>
				</div>
				<div class="features__item">
					<img src="img/eclips3.svg" alt="" class="features__item-img">
					<h4 class="features__item-title">Огромное сообщество</h4>
					<p class="features__item-text">Сейчас в SUS более 20 000 участников.<br>
						Вы попали в лучшее место, чтобы обсуждать,<br>
						критиковать, играть и объединяться!</p>
				</div>
			</div>
		</div>
		<div class="game__rez">
			<div class="game__rez__text">
				<h5 class="game__rez__title">ИГРОВЫЕ РЕЖИМЫ</h5>
				<p class="game__rez__text-p">Сервера с этими игровыми режимами можно найти в <span class="game__rez__text-color">Servers User Score</span></p>
			</div>
			<div class="game__rez-img">
				<div class="game__rez__item">
					<img class="game__rez__item__img" src="img/dayz.png" alt="">
					<p class="game__rez__item__text">DayZ (Vanilla / ++)</p>
				</div>
				<div class="game__rez__item">
					<img class="game__rez__item__img" src="img/dayzstalker.png" alt="">
					<p class="game__rez__item__text">DayZ Stalker</p>
				</div>
				<div class="game__rez__item">
					<img class="game__rez__item__img" src="img/gmod.png" alt="">
					<p class="game__rez__item__text">Legacy Gamemodes</p>
				</div>
				<div class="game__rez__item">
					<img class="game__rez__item__img" src="img/darkrp.png" alt="">
					<p class="game__rez__item__text">GMOD Role Play</p>
				</div>
				<div class="game__rez__item">
					<img class="game__rez__item__img" src="img/unt.png" alt="">
					<p class="game__rez__item__text">Unturned</p>
				</div>
			</div>
		</div>
	</div>
</section>

<section class="opinion">
	<div class="container">
		<h6 class="opinion-title"><span class="opinion-title-col">Мнение</span> важнее всего</h6>
		<div class="content__opinion">
			<div class="content__opinion__text">
				<div class="opinion__item">
					<h3 class="opinion__item-title-nonimg">Ваши отзывы - ценность сообщества</h3>
					<p class="opinion__item-text-nonimg">User Score - часть нашего названия, именно это и означает: 
						оценка пользователей. Мы предлагаем широкий 
						инструментарий для оценки и критики серверов.
					</p>
				</div>
				<div class="opinion__item">
					<img class="opinion__item-img" src="img/60uscko.svg" alt="">
					<h3 class="opinion__item-title">USER SCORE</h3>
					<p class="opinion__item-text">Это оценка удовлетворенности сообщества. Эту оценку 
						может поставить любой участник SUS. Вы можете оценить,
						нравится вам сервер, или нет, используя кнопку “нравится”, 
						или кнопку “не нравится”. Поставленные оценки не проходят
						модерацию. 
					</p>
				</div>
				<div class="opinion__item">
					<img class="opinion__item-img" src="img/25revcko.svg" alt="">
					<h3 class="opinion__item-title">REVIEW SCORE</h3>
					<p class="opinion__item-text">Это оценка сервера, сформированная на основании оценок
						его игроков. Оценка рассчитывается по формуле среднего 
						взвешенного.  Ревью проходят проверку командой модерации
						перед публикацией. На страже честности ревью стоит система  
						FAIRSCORE, проверяющая, действительно ли ревьер играл на
						сервере, о котором собирается написать свое ревью. 
					</p>
				</div>
			</div>
			<img class="opinion__image" src="img/women.svg" alt="">
		</div>
		<div class="estimate">
			<h4 class="estimate__title">Хотите оценить несколько серверов?</h4>
			<!-- svelte-ignore a11y-invalid-attribute -->
			<a class="estimate__button" href=""><img class="estimate__button__img" src="img/discord.svg" alt="">Подключится</a>
		</div>
	</div>
</section>

<section class="foradm">
	<div class="container">
		<div class="content__foradm">
			<div class="foradm__item">
				<h1 class="foradm__title">SUS ДЛЯ АДМИНОВ</h1>
				<p class="foradm__text">Servers User Score готов включить ваш сервер в список Войдите, чтобы добавить сервер в наши списки и стать частью
					огромного сообщества!
				</p>
				<!-- svelte-ignore a11y-invalid-attribute -->
				<a class="foradm__button" href=""><img class="foradm__button__img" src="img/men+.svg" alt="">Создать аккаунт</a>
			</div>
			<img src="img/serv.svg" alt="" class="foradm__image">
		</div>
	</div>
</section>

<section class="hiw">
	<div class="container">
		<div class="content__hiw">
			<img class="hiw__image" src="img/hiw.svg" alt="">
			<div class="hiw__text">
				<h2 class="hiw__title__title">Как это работает?</h2>
				<p class="hiw_title__text">Используйте SUS как универсальное средство для
				продвижения и общения с вашим сообществом.
				Новички очень часто ищут сервера, используя SUS. 
				Давайте поможем им найти Вас!</p>
				<div class="hiw__item">
					<img src="img/eclpep.svg" alt="" class="hiw__item__img">
					<div class="hiw__item__strip1"></div>
					<h4 class="hiw__item__title">Зарегистрируйтесь</h4>
					<p class="hiw_item__text">Создайте аккаунт в нашей системе,<br> 
						чтобы добавить сервер в нашей
						удобной форме.
					</p>
				</div>
				<div class="hiw__item">
					<img src="img/eclgalg.svg" alt="" class="hiw__item__img">
					<div class="hiw__item__strip2"></div>
					<h4 class="hiw__item__title">Убедитесь, что сервер подходит</h4>
					<p class="hiw_item__text">Мы добавляем сервера, если на их Discord
						сервере имеется более 300 участников, он
						доступен для игры в момент добавления,  Увы,
						сервера в разработке мы не добавляем =(
					</p>
				</div>
				<div class="hiw__item__notstrip">
					<img src="img/eclblank.svg" alt="" class="hiw__item__img">
					<h4 class="hiw__item__title">Заполните форму</h4>
					<p class="hiw_item__text">Заполните данные о Вашем сервере, чтобы
						мы могли отобразить их. Дождитесь, когда 
						сервер пройдет модерацию, и воуаля! 
						Ваш сервере уже в SUS!
					</p>
				</div>
			</div>
		</div>
		<div class="add__server">
			<h4 class="add__server__title">Готовы добавить ваш сервер?</h4>
			<!-- svelte-ignore a11y-invalid-attribute -->
			<a class="add__server__button" href=""><img class="add__server__button__img" src="img/serevlogo.svg" alt="">Добавить сервер</a>
		</div>
	</div>
</section>



<style>
	.main{
		background-repeat: no-repeat;
		background-size: 100% 100%;
		background-color: gray;
		width: 100vw;
		height: 900px;
		background: url(img/topglav-bg.png) center;
	}
	.content{
		display: flex;
		position: relative;
		top: 200px;
		justify-content: space-between;
	}

	.container{
		max-width: 1520px;
		margin: 0 auto;
		padding-left: 15px;
		padding-right: 15px;
	}

	.content__button{
		display: inline-block;
		position: relative;	
		padding: 15px 35px;
		background-color: #CE3727;
		text-decoration: none;
		color: #fff;
		border-radius: 15px;
		font-size: 23px;
		width: 180px;
		text-align: right;
	}

	.content__button__img{
		position: absolute;
		width: 30px;
		top: 18px;
		left: 30px;
	}

	.content__text{
		text-align: center;
		margin-top: 11px;
		color: #fff;
	}

	.content__title{
		font-size: 118px;
		font-weight: bold;
	}

	.content__slowtext{
		font-size: 32px;
		margin-top: -80px;
	}

	.content__image{
		margin-left: -351px;
	}

	.content__img{
		width: 1000px;
		display: block;
		max-width: 100%;

	}

	.scrol__img{
		display: block;
		margin: 0 auto;
		margin-top: 120px;
	}

	
	.features__title{
		text-align: center;
		font-weight: 600;
		font-size: 48px;
	}

	.features__title__color{
		background: linear-gradient(84.6deg, #EF3421 11.38%, #EF852F 52.2%);
		-webkit-background-clip: text;
		-webkit-text-fill-color: transparent;
		background-clip: text;
	}
	.content__features{
		display: flex;
		margin-top: 75px;
		justify-content: center;
		margin-left: -155px;
		font-weight: 600;
		font-size: 96px;
		line-height: 80px;
	}

	.content__features__image{
		position: relative;
		margin-right: 54px;
	}

	.features__item-title{
		position: relative;
		font-style: normal;
		font-weight: 600;
		font-size: 32px;
		line-height: 40px;
		color: #2D2D2D;
		top: -115px;
		left: 75px;
	}
	
	.features__item-text{
		font-style: normal;
		font-weight: 400;
		font-size: 16px;
		line-height: 20px;
		letter-spacing: 0.01em;
		color: #2D2D2D;
		position: relative;
		top: -155px;
		left: 75px;
	}
	.features__item{
		margin-top: -143px;
	}

	.content__features__text{
		margin-top: 138px;
	}
	
	.game__rez__text{
		text-align: center;
	}

	.game__rez__title{
		font-size: 48px;
		font-weight: 600;
		color: #171617;
	}

	.game__rez__text-p{
		font-size: 20px;
		font-weight: 400;
		color: #171617;
		margin-top: -80px;
	}

	.game__rez__text-color{
		background: linear-gradient(90.45deg, #EF3421 77.41%, #EF852F 77.93%);
		-webkit-background-clip: text;
		-webkit-text-fill-color: transparent;
		background-clip: text;
	}

	.game__rez{
		margin-top: -180px;
	}

	.game__rez-img{
		display: flex;
		gap: 30px;
		align-items: center;
		justify-content: center;
		flex-wrap: wrap;
	}

	.game__rez__item__img{
		margin-top: 10px;
	}
	
	.game__rez__item{
		width: 200px;
		height: 125px;
		background: #fff;
		border-radius: 10px;
		filter: drop-shadow(0px 0px 15px rgba(0, 0, 0, 0.14));
	}

	.game__rez__item__text{
		text-align: center;
		font-weight: 400;
		font-size: 16px;
		line-height: 20px;
		letter-spacing: 0.03em;
		color: #000000;
		margin: 0;
	}

	/* Opinion */

	.opinion{
		margin-top: -50px;
		height: 950px;
		background: #F3F3F3 no-repeat;
	}

	.opinion-title{
		font-size: 48px;
		font-weight: 600;
		text-align: center;
		padding-top: 50px;
	}
	.opinion-title-col{
		background: linear-gradient(267.66deg, #EF852F 10%, #EF3421 92.84%);
		-webkit-background-clip: text;
		-webkit-text-fill-color: transparent;
		background-clip: text;
	}
	
	.content__opinion{
		display: flex;
		justify-content: center;
		margin-top: -70px;
	}

	.opinion__item:nth-child(3){
		margin-top: -17px;
	}

	.opinion__item-title-nonimg{
		font-weight: 600;
		font-size: 32px;
		line-height: 34px;
		text-transform: capitalize;
		color: #2D2D2D;
		width: 541px;
		height: 34px;
	}

	.opinion__item-text-nonimg{
		width: 430px;
		height: 60px;
		font-weight: 400;
		font-size: 16px;
		line-height: 20px;
		letter-spacing: 0.01em;
		color: #2D2D2D;
		margin-top: -20px;
	}
	
	.opinion__item-title{
		position: relative;
		width: 205px;
		height: 34px;
		font-weight: 600;
		font-size: 32px;
		line-height: 34px;
		color: #2D2D2D;
		top: -90px;
		left: 123px;
	}

	.opinion__item-text{
		max-width: 455px;
		min-width: 420px;
		height: 100px;
		font-weight: 400;
		font-size: 16px;
		line-height: 20px;
		letter-spacing: 0.01em;
		color: #2D2D2D;
		margin-top: -95px;
	}

	.opinion__image{
		margin-left: -105px;
		margin-top: 75px;
		width: 534px;
		height: 422px;
	}


	.estimate__button{
		display: inline-block;
		position: relative;	
		padding: 15px 70px;
		background-color: #CE3727;
		text-decoration: none;
		color: #fff;
		border-radius: 15px;
		font-size: 23px;
		width: 100px;
		margin: 0 auto;
		display: block;
	}

	.estimate__button__img{
		position: absolute;
		width: 30px;
		top: 18px;
		left: 27px;
	}

	.estimate__title{
		font-weight: 600;
		font-size: 32px;
		line-height: 26px;
		text-align: center;
		color: #171617;
	}

	.estimate{
		margin-top: 90px;
	}

	.foradm{
		background-color: #211918;
		color: #fff;
		height: 397px;
	}

	.content__foradm{
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.foradm__button{
		display: flex;
		background: #CE3727;
		box-shadow: 0px 8px 20px rgba(206, 55, 39, 0.4);
		border-radius: 15px;
		padding: 12px 55px;
		width: 186px;
		height: 30px;
		font-style: normal;
		font-weight: 400;
		font-size: 24px;
		line-height: 30px;
		text-align: right;
		color: #FFFFFF;
		text-decoration: none;
		white-space: nowrap;
	}

	.foradm__button__img{
		width: 40px;
		position: relative;
		left: -25px;
	}

	.foradm__title{
		width: 320px;
		height: 112px;
		font-weight: 700;
		font-size: 64px;
		line-height: 60px;
	}

	.foradm__text{
		width: 555px;
		height: 60px;
		font-weight: 400;
		font-size: 20px;
		line-height: 20px;
		margin-top: -20px;
	}
	
	.foradm__image{
		margin-left: 172px;
		margin-top: 60px;
	}


	
	.hiw{
		background-color: #171617;
		height: 920px;
	}

	.content__hiw{
		display: flex;
		justify-content: center;
	}

	.hiw__title__title{
		width: 314px;
		height: 39px;
		font-weight: 600;
		font-size: 32px;
		line-height: 48px;
		color: #F3F3F3;
	}

	.hiw_title__text{
		margin-top: -5px;
		width: 389px;
		height: 76px;
		font-weight: 400;
		font-size: 16px;
		line-height: 19px;
		letter-spacing: 0.03em;
		color: #F3F3F3;
	}

	.hiw__text{
		margin-left: 36px;
		margin-top: 30px;
	}

	.hiw__item__strip1{
		width: 58px;
		height: 0px;
		border: 1px solid #F3F3F3;
		transform: rotate(90deg);
		position: relative;
		left: 9px;
		top: 10px;
	}
	.hiw__item__strip2{
		width: 88px;
		height: 0px;
		border: 1px solid #F3F3F3;
		transform: rotate(90deg);
		position: relative;
		top: 26px;
		left: -5px;
	}

	.hiw__item__title{
		width: 463px;
		height: 40px;
		font-weight: 600;
		font-size: 32px;
		line-height: 40px;
		color: #F3F3F3;
		margin-left: 80px;
		margin-top: -75px;
	}

	.hiw_item__text{
		width: 350px;
		height: 60px;
		font-weight: 400;
		font-size: 16px;
		line-height: 20px;
		letter-spacing: 0.03em;
		color: #F3F3F3;
		margin-left: 80px;
		margin-top: -31px;
	}

	.hiw__item__notstrip{
		margin-top: 45px;
	}

	.hiw__image{
		margin-top: 65px;
	}

	.add__server__button{
		display: flex;
		background: #CE3727;
		box-shadow: 0px 8px 20px rgba(206, 55, 39, 0.4);
		border-radius: 15px;
		padding: 15px 55px;
		width: 186px;
		height: 30px;
		font-style: normal;
		font-weight: 400;
		font-size: 24px;
		line-height: 30px;
		text-align: right;
		color: #FFFFFF;
		text-decoration: none;
		margin: -20px auto;
		white-space: nowrap;
	}

	.add__server__button__img{
		width: 30px;
		position: relative;
		left: -25px;
	}

	.add__server__title{
		text-align: center;
		height: 26px;
		font-weight: 600;
		font-size: 32px;
		line-height: 26px;
		color: #FFFFFF;
	}

	.add__server{
		margin-top: 60px;
		display: grid;
	}

	@media (max-width: 1432px) {
		.content__img{
			width: 900px;
		}
		.content__image{
			margin-left: -315px;
		}
	}
	@media (max-width: 1368px) {
		.content__img{
			width: 850px;
		}
		.content__image{
			margin-left: -298px;
		}
	}
	@media (max-width: 1300px) {
		.content__img{
			width: 800px;
		}
		.content__image{
			margin-left: -279px;
		}
		.content__title{
			font-size: 100px;
		}
		.content__slowtext{
			font-size: 30px;
			margin-top: -70px;
		}
	}

	@media (max-width: 1200px) {
		.content__img{
			width: 760px;
		}
		.content__image{
			margin-left: -267px;
		}
		.content__title{
			font-size: 95px;
		}
		.content__slowtext{
			font-size: 26px;
			margin-top: -70px;
		}

		.content__opinion{
			margin-top: -150px;
		}
	}

	@media (max-width: 1132px) {
		.content__img{
			width: 720px;
		}
		.content__image{
			margin-left: -252px;
		}
		.content__title{
			font-size: 94px;
		}
		.content__slowtext{
			font-size: 24px;
			margin-top: -70px;
		}
	}

	@media (max-width: 1024px) {
		.content__img{
			width: 680px;
		}
		.content__image{
			margin-left: -239px;
		}
		.content__title{
			font-size: 85px;
		}
		.content__slowtext{
			font-size: 22px;
			margin-top: -70px;
		}
		.scrol__img{
			margin-top: 220px;
		}
		.content__features__image{
			margin-right: 20px;
			left: 60px;
		}
		.content__features__img{
			width: 90%;
		}
		.foradm__image{
			margin-left: 0;
		}
		.hiw__image {
			width: 95%;
		}
		.opinion__image{
			width: 95%;
		}
		.opinion-title{
			font-size: 70px;
		}
		.foradm__text {
			font-size: 18px;
		}
	}
	@media (max-width: 946px) {
		.content__img{
			width: 620px;
		}
		.content__image{
			margin-left: -216px;
		}
		.content__title{
			font-size: 74px;
		}
		.content__slowtext{
			font-size: 20px;
			margin-top: -60px;
		}
		.scrol__img{
			margin-top: 220px;
		}
		.content__features__image{
			margin-right: 20px;
			left: 120px;
		}
		.content__features__img{
			width: 80%;
		}
		.content__features{
			margin-left: -215px;
		}
	}

	@media (max-width: 876px) {
		.content__img{
			width: 570px;
		}
		.content__image{
			margin-left: -200px;
		}
		.content__title{
			font-size: 74px;
		}
		.content__slowtext{
			font-size: 15px;
			margin-top: -55px;
		}
		.scrol__img{
			margin-top: 260px;
		}
		.content__features__image{
			margin-right: 10px;
			left: 150px;
		}
		.content__features__img{
			width: 70%;
		}
		
		.content__features{
			margin-left: -215px;
		}

		.foradm__image{
			width: 35%;
		}
		.foradm__title{
			font-size: 54px;
		}

		.foradm__text{
			width: 444px;
		}
	}

	@media (max-width: 852px) {
		.content__features__image{
			margin-right: 0;
			left: 140px;
		}
		.features__item{
			margin-left: -30px;
		}
	}

	@media (max-width: 804px) {
		.content__title{
			font-size: 65px;
		}
		.content__slowtext{
			font-size: 13px;
			margin-top: -46px;
		}
		.content__img{
			width: 520px;
		}
		.content__image{
			margin-left: -181px;
		}
		.content__features__image{
			margin-right: 0;
			left: 143px;
		}
		.content__features__img{
			width: 60%;
		}
		.features__item{
			margin-left: -80px;
		}
	}

	@media (max-width: 768px) {
		.content__img{
			display: none;
		}
		.content__features__img{
			display: none;
		}
		.opinion__image{
			display: none;
		}
		.foradm__image{
			display: none;
		}
		.hiw__image{
			display: none;
		}
		.content{
			justify-content: center;
		}
		.content__text{
			margin-left: 170px;	
		}
		.content__features{
			margin-left: 0;
		}

		.scrol__img{
			margin-top: 390px;
		}
		.foradm__item{
			text-align: center;
		}
		.foradm__title{
			text-align: center;
			margin: 0 auto;
			margin-bottom: 20px;
			margin-top: 55px;
		}
		.foradm__text{
			text-align: center;
			margin: 0 auto;
			margin-bottom: 20px;
		}
		.foradm__button{
			margin: 0 auto;
		}
		.estimate{
			margin-top: 50px;
		}
		.opinion-title{
			font-size: 50px;
			margin-bottom: 150px;
		}

		.opinion{
			height: 880px;
		}
	}

	@media (max-width: 490px) {
		.opinion__item-title-nonimg{
			font-size: 25px;
		}
		.opinion__item-title{
			font-size: 25px;
			top: -85px;
		}
		.content__opinion__text{
			margin-left: 90px;
		}
		.opinion{
			height: 920px;
		}

		.hiw__item__title{
			font-size: 24px;
		}

		.hiw__title__title{
			margin-left: 20px;
		}

		
		.hiw_title__text{
			margin-left: 20px;
		}

		.hiw__text{
			margin-left: 95px;
		}
	}
	
	@media (max-width: 442px) {
		.opinion__item-title-nonimg{
			font-size: 20px;
		}
		.opinion__item-text-nonimg{
			font-size: 15px;
		}
		.opinion__item-title{
			font-size: 20px;
			top: -75px;
			left: 110px;
		}
		.opinion__item-text{
			font-size: 15px;
			margin-top: -83px;
			max-width: 400px;
			min-width: 350px;
		}

		.opinion__item-img{
			width: 20%;
		}
		.opinion__item:nth-child(3){
			margin-top: 15px;
		}
		.content__opinion__text{
			margin-left: 140px;
		}
		.foradm__text{
			font-size: 18px;
			width: 400px;
		}
		.add__server__button{
			margin: 0 auto;
		}
		.estimate__title{
			margin-top: 70px;
		}
	}


</style>
