<style>
	/*вот так ставятся комментарии внутри style*/

	/* ВСЯ ШАПКА */
	.header {
		background-color: gray;
		height: 100px;
		font-family: arial;
	}
	/* ЦЕНТРАЛЬНЫЙ ГЛАВНЫЙ ДИВ */
	.charts-container {
		width: 1000px;
		height: 2000px;
		background-color: white;
		margin-left: auto;
		margin-right: auto;
		font-family: arial;

	}

	/* ДИВ, КОТОРЫЙ СОДЕРЖИТ ДИВЫ ДЛЯ ЛОГОТИПА, ССЫЛОК И КНОПКИ */
	.header-center {
		height: 95px;
		background-color: gray;
		width: 1000px;
		margin-left: auto;
		margin-right: auto;
		display: flex;
	}
	/* ДИВ ДЛЯ ЧЕТЫРЕХ КНОПОК СОРТИРОВКИ */
	.charts-sort {
		background-color: white;
		height: 100px;
		width: 1000px;
		margin-left: auto;
		margin-right: auto;
		
	}
	/* ДИВ ДЛЯ ПЕСНИ, КОТОРАЯ ПОДНЯЛАСЬ В РЕЙТИНГЕ ПЕСЕН */
	.charts-up {
		height: 200px;
		width: 1000px;
		margin-left: auto;
		margin-right: auto;
		background-color: C5EDD1;
		border-radius: 10px;
		margin-top: 10px;
		display: flex;
	}
	/* ДИВ ДЛЯ НОВОЙ ПЕСНИ, КОТОРАЯ ПОПАЛА В РЕЙТИНГ ПЕСЕН */
	.charts-new {
		height: 200px;
		width: 1000px;
		margin-left: auto;
		margin-right: auto;
		background-color: FFE7BA;
		border-radius: 10px;
		margin-top: 10px;
		display: flex;
	}
	/* ДИВ ДЛЯ ПЕСНИ, КОТОРАЯ ОПУСТИЛАСЬ В РЕЙТИНГЕ ПЕСЕН */
	.charts-down {
		height: 200px;
		width: 1000px;
		margin-left: auto;
		margin-right: auto;
		background-color: EDC2C2;
		border-radius: 10px;
		margin-top: 10px;
		display: flex;
	}
	/* ДИВ ДЛЯ ЛОГОТИПА САЙТА*/
	.box-logo {
		height: 95px;
		width: 200px;
		
		 
	}
	/* ДИВ ДЛЯ ЧЕТЫРЕХ ССЫЛОК САЙТА*/
	.box-links {
		height: 65px;
		width: 650px;
		padding-top: 30px;
		 
	}
	/* ДИВ ДЛЯ КНОПКИ "SUBSCRIBE" */
	.box-buttons {
		height: 95px;
		width: 150px;
		
		 
	}
	/* ДИВ ДЛЯ НОМЕРА И СТАТУСА ПЕСНИ В РЕЙТИНГЕ */
	.charts-rank {
		width: 120px;
		height: 160px;
		text-align: center;
		padding-top: 40px;	
	}
	/* ДИВ ДЛЯ НАЗВАНИЯ И ИСПОЛНИТЕЛЯ ПЕСНИ */
	.charts-info {
		width: 550px;
		height: 180px;
		padding-top: 20px;
		font-weight: 700;
		font-size: 25px
	}
	/* ДИВ ДЛЯ КНОПОК ПЕСНИ */
	.charts-button {
		width: 180px;
		height: 180px;
		padding-top: 20px;
		
	}
	/* ДИВ ДЛЯ КАРТИНКИ ПЕСНИ ИЛИ АЛЬБОМА */
	.charts-img {
		width: 150px;
		height: 200px;
		
		
	}
	/* ЧЕТЫРЕ ССЫЛКИ В ШАПКЕ */
	.links-header {
		margin-left: 50px;
		color: white;
	}
	/* ФИОЛЕТОВАЯ КНОПКА */
	.button-purple {
		background-color: purple;
		color: white;
		margin-top: 20px;
		width: 150px;
		height: 40px;
		border: none;
		border-radius: 5px;
	}
	/* СИНЯЯ КНОПКА */
	.button-blue {
		background-color: blue;
		color: white;
		margin-top: 20px;
		width: 160px;
		height: 40px;
		border: none;
		border-radius: 5px;
	}
	/* ЗЕЛЕНАЯ КНОПКА */
	.button-green {
		background-color: green;
		margin-top: 20px;
		width: 150px;
		height: 40px;
		border-radius: 5px;
		
	}

	/* КРАСНАЯ КНОПКА */
	.button-red {
		background-color: red;
		color: white;
		margin-top: 20px;
		width: 150px;
		height: 40px;
		border: none;
		border-radius: 5px;
	}
	.button-yellow{
		background-color: orange;
		margin-top: 20px;
		width: 150px;
		height: 40px;
		border-radius: 5px;
	}

	/* ТЕКСТ СТАТУСА ПЕСНИ, КОТОРАЯ ПОДНЯЛАСЬ В РЕЙТИНГЕ */
	.charts-rank-text-up {
		font-weight: 700;
		color: green;
	}
	/* ТЕКСТ СТАТУСА ПЕСНИ, КОТОРАЯ НЕДАВНО ПОПАЛА В РЕЙТИНГ */
	.charts-rank-text-new {
		font-weight: 700;
		color: orange;
	}
	/* ТЕКСТ СТАТУСА ПЕСНИ, КОТОРАЯ ОПУСТИЛАСЬ В РЕЙТИНГЕ */
	.charts-rank-text-down {
		font-weight: 700;
		color: red;
	}
	/* НАЗВАНИЕ ПЕСНИ */
	.charts-info-songname {
		color: blue;
	}
	/* НАЗВАНИЕ ИСПОЛНИТЕЛЯ */
	.charts-info-artistname {
		color: gray;
	}
	/* КАРТИНКА ДЛЯ ПЕСНИ */
	.charts-img-size {
		width: 150px;
		margin-top: 40px;
	}
	.img-logo{
		width: 200px;
		margin-top: 15px;
	}
</style>

<!-- 1 уровень. шапка -->
<div class="header">
	<!-- 2 уровень. выравнивание шапки -->
	<div class="header-center">
		<!-- 3 уровень -->
		<!-- лого -->
		<div class="box-logo">
			<img class="img-logo" src="https://www.pngkit.com/png/full/234-2341310_billboard-logo-png-clip-black-and-white-2018.png">
		</div>
		<!-- ссылки -->
		<div class="box-links">
			<a class="links-header" href="">CHARTS</a>
			<a class="links-header" href="">NEWS</a>
			<a class="links-header" style="color: red" href="">VIDEO</a>
			<a class="links-header" style="color: orange" href="">PHOTOS</a>
		</div>
		<!-- кнопка подписаться -->
		<div class="box-buttons">
			<button class="button-purple">subscribe</button>
		</div>
	</div>
</div>

<!-- 1 уровень. чарт-контейнер -->
<div class="charts-container">
	<!-- 2 уровень -->
	<!-- для кнопок сортировки -->
	<div class="charts-sort">
		<button class="button-yellow">THIS WEEK</button>
		<button class="button-red">LAST WEEK</button>
		<button class="button-green">PEAK</button>
		<button class="button-purple">DURATION</button>
	</div>
	<!--все треки в чарте -->

	<!-- трек up -->
	<div class="charts-up">
		<!-- 3 уровень -->
		<!-- Место в чате -->
		<div class="charts-rank">
			<h1>1</h1>
			<p class="charts-rank-text-up">Up</p>
		</div>
		<!-- информация о треке -->
		<div class="charts-info">
			<p class="charts-info-songname">Duele ele corazon</p>
			<p class="charts-info-artistname">Энрике Иглесиас</p>
		</div>
		<!-- купить или воспроизвести -->
		<div class="charts-button">
			<button class="button-blue"> воспроизвести </button>
		</div>
		<!-- картинка -->
		<div class="charts-img">
			<img class="charts-img-size" src="index.jpg">
		</div>
	</div>

	<!-- трек new -->
	<div class="charts-new">
		<!-- 3 уровень -->
		<!-- Место в чате -->
		<div class="charts-rank">
			<h1>2</h1>
			<p class="charts-rank-text-new">New</p>
		</div>
		<!-- информация о треке -->
		<div class="charts-info">
			<p class="charts-info-songname">Bella Ciao</p>
			<p class="charts-info-artistname">Ману Пилас</p>
		</div>
		<!-- купить или воспроизвести -->
		<div class="charts-button">
			<button class="button-green">Купить</button>
		</div>
		<!-- картинка -->
		<div class="charts-img">
			<img class="charts-img-size" src="index2.png">
		</div>
	</div>

	<!-- трек new -->
	<div class="charts-new">
		<!-- 3 уровень -->
		<!-- Место в чате -->
		<div class="charts-rank">
			<h1>3</h1>
			<p class="charts-rank-text-new">New</p>
		</div>
		<!-- информация о треке -->
		<div class="charts-info">
			<p class="charts-info-songname">In This Shirt</p>
			<p class="charts-info-artistname">The Irrepressibles</p>
		</div>
		<!-- купить или воспроизвести -->
		<div class="charts-button">
			<button class="button-green"> купить </button>
		</div>
		<!-- картинка -->
		<div class="charts-img">
			<img class="charts-img-size" src="index3.jpg">
		</div>
	</div>

	<!-- трек up -->
	<div class="charts-up">
		<!-- 3 уровень -->
		<!-- Место в чате -->
		<div class="charts-rank">
			<h1>4</h1>
			<p class="charts-rank-text-up">Up</p>
		</div>
		<!-- информация о треке -->
		<div class="charts-info">
			<p class="charts-info-songname">You're Gonna Go Far, Kid</p>
			<p class="charts-info-artistname">The Offspring</p>
		</div>
		<!-- купить или воспроизвести -->
		<div class="charts-button">
			<button class="button-green">Купить</button>
		</div>
		<!-- картинка -->
		<div class="charts-img">
			<img class="charts-img-size" src="index4.jpg">
		</div>
	</div>

	<!-- трек down -->
	<div class="charts-down">
		<!-- 3 уровень -->
		<!-- Место в чате -->
		<div class="charts-rank">
			<h1>5</h1>
			<p class="charts-rank-text-down">Down</p>
		</div>
		<!-- информация о треке -->
		<div class="charts-info">
			<p class="charts-info-songname">Old Town Road</p>
			<p class="charts-info-artistname">Billy Ray Cyrus</p>
		</div>
		<!-- купить или воспроизвести -->
		<div class="charts-button">
			<button class="button-green">Купить</button>
		</div>
		<!-- картинка -->
		<div class="charts-img">
			<img class="charts-img-size" src="index5.jpg">
		</div>
	</div>

	<!-- трек new -->
	<div class="charts-new">
		<!-- 3 уровень -->
		<!-- Место в чате -->
		<div class="charts-rank">
			<h1>6</h1>
			<p class="charts-rank-text-new">New</p>
		</div>
		<!-- информация о треке -->
		<div class="charts-info">
			<p class="charts-info-songname">Cant Hold Us</p>
			<p class="charts-info-artistname"> Маклемор и Райан Льюис </p>
		</div>
		<!-- купить или воспроизвести -->
		<div class="charts-button">
			<button class="button-blue">воспроизвести</button>
		</div>
		<!-- картинка -->
		<div class="charts-img">
			<img class="charts-img-size" src="index6.jpg">
		</div>
	</div>

	<!-- трек up -->
	<div class="charts-up">
		<!-- 3 уровень -->
		<!-- Место в чате -->
		<div class="charts-rank">
			<h1>7</h1>
			<p class="charts-rank-text-up"> Up</p>
		</div>
		<!-- информация о треке -->
		<div class="charts-info">
			<p class="charts-info-songname">Impossible</p>
			<p class="charts-info-artistname">james Arthur</p>
		</div>
		<!-- купить или воспроизвести -->
		<div class="charts-button">
			<button class="button-blue">воспроизвести</button>
		</div>
		<!-- картинка -->
		<div class="charts-img">
			<img class="charts-img-size" src="index8.jpg">
		</div>
	</div>
</div>
<!--  -->
