# stark-indastriz2.0
<!DOCTYPE html>
<html lang=«en»>

<head>
	<meta charset=«UTF-8»>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title> Stark Indastriz.com</title>
	<link rel="icon" href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTWXzeK1ibi6wz5P4knBdmMpC145Bbbs0KamA&usqp=CAU" type="image/png">
	<link rel="stylesheet" href="style.css">
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js" integrity="sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+" crossorigin="anonymous"></script>
	<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">
	<style>
		body {
			background-image: url(https://oir.mobi/uploads/posts/2021-03/thumbs/1616988837_52-p-fon-dlya-prilozheniya-53.jpg);
			margin: 0;

		}

		* {
			margin: 0;
			padding: 0;
		}

		/*шапка головного меню*/
		#login-form {
			margin-right: 20px;
			position: absolute;
			top: 45px;
			right: 0px;
			width: 240px;
			padding: 10px;
			background: #444;
			border: 1px solid #ccc;
			z-index: 2;
		}


		.menu {

			width: auto;
			height: 25px;
			background-color: #444;

		}

		.menu-x {

			padding: 0;
			margin: 0;
			list-style: none;
			display: flex;
			justify-content: center;
			background-color: #444;

		}

		.menu-x li {
			margin-left: 10px;
		}

		.menu-x a {
			color: white;
			text-decoration: none;
		}

		.header {
			align-items: center;
			display: flex;
			width: auto;
			height: 57px;
			background-color: #303030;


		}

		.header-logo {
			color: white;
			margin-top: 10px;
			padding-left: 20px;
		}

		.button btn {

			width: 90px;
			height: 30px;
			color: white;
			background-color: #e12f2f;
			display: block;


		}


		.dropdown-button {
			display: flex;
			align-items: center;
			justify-content: center;
			padding: 2px;
			background-color: #e12f2f;
			left: 10px;
			position: relative;
		}

		.dropdown-list {
			position: absolute;
			top: 9%;
			left: 130px;
			display: none;
			padding: 0;
			margin: 0;
			list-style: none;
			background-color: #fff;
			border: 1px solid #ccc;
			z-index: 1;
		}

		.dropdown-list li {
			color: currentColor;

		}

		.dropdown-button:focus+.dropdown-list,
		.dropdown-list:focus {
			display: block;

		}


		.selektor {
			margin-left: 10px;
			border: none;
			background: none;
			color: white;
			justify-content: center;
		}

		.list {
			color: #303030;
		}

		.input {
			left: 15px;
			width: 400px;
			height: 30px;
			color: #000000;
			border: none;
			background: white;
		}

		.button {
			margin-left: auto;
			border: none;
			width: 40px;
			height: 30px;
			margin-left: 0px;
			color: white;
			background-color: #e12f2f;
		}

		.bi bi-search {
			background-color: #e12f2f;
		}

		.form-input {
			align-items: center;
			margin-left: 15px;
			display: flex;
		}

		.icon {
			align-items: center;
			list-style: none;
			font-size: 20px;
			border: 50px;
			padding: 0;
			display: flex;
			color: white;



		}

		.person {
			padding-left: 40px;
			cursor: pointer;

		}

		.heart {
			padding-left: 40px;
			cursor: pointer;
		}

		.cart3 {
			padding-left: 40px;
			cursor: pointer;
		}

		.carousel-inner {
			margin-bottom: 10px;
			width: 50px;
			height: 200px;
		}

		/*карточка товара*/

		main {
			padding: 20px;
		}

		section {
			margin-bottom: 20px;
		}

		.product {
			align-items: center;
			color: white;
			background-color: #000;
			margin-left: 15px;
			display: inline-block;
			width: 200px;
			margin: 10px;
		}

		.product img {
			width: 100%;
		}

		.product h3 {
			margin-top: 10px;
		}

		.product p.price {
			font-weight: bold;
		}

		.forms {
			margin: 4px;
			background-color: #303030;
			width: 480px;
		}

		.forms ul {
			color: white;
			text-decoration: none;
		}

		.sidebar {
			width: 100px;
			height: 50px;
			background-color: #303030;
			margin-left: 5px;
			color: white;

		}

		.sidebar ul {
			text-decoration: none;
		}

		/*подвал*/
		footer {
			color: white;
			background-color: #444;
			padding: 20px;
			text-align: center;
		}

		.container {
			max-width: 960px;
			margin: 0 auto;
		}

		p {
			margin: 0;
		}
	</style>

</head>

<body>
	<div class="header">
		<div class="header-logo">
			<h4>Stark Indastriz</h4>
		</div>


		<button class="dropdown-button" id="button"><i class="bi bi-grid-3x3-gap-fill"></i>Каталог</button>
		<ul class="dropdown-list" id="list">
			<li>телефоны</li>
			<li>планшеты</li>
			<li>ноутбуки</li>
			<li>компьютеры</li>
			<li>телевизоры</li>

		</ul>


		<div id="start"></div>
		<div class="form-input">
			<input class="input"><button class="button"><i class="bi bi-search"></i></button>
		</div>

		<div class="icon">
			<div class="heart">
				<i class="bi bi-heart"></i>
			</div>
			<div class="cart3">
				<i class="bi bi-cart3"></i>
			</div>
			<div class="person">
				<i class="bi bi-person-circle" id="login-btn"></i>
				<div id="login-form" style="display: none;">
					<form>
						<label for="username">Имя пользователя</label>
						<input type="text" id="username" name="username">
						<label for="password">Пароль</label>
						<input type="password" id="password" name="password">
						<input href="test-1.html" type="submit" value="Войти">
					</form>
				</div>

			</div>
		</div>



	</div>


	<nav class="menu">
		<ul class="menu-x">
			<li><a href="#">Магазины</a></li>
			<li><a href="#">Акции</a></li>
			<li><a href="#">Бонусы</a></li>

			<select class="selektor">
				<option class="list">Киев</option>
				<option class="list">Днепр</option>
				<option class="list">Одесса</option>
				<option class="list">Харьков</option>
				<option class="list">Житомир</option>
			</select>
		</ul>
	</nav>



	<div id="carouselExample" class="carousel slide">
		<div class="carousel-inner">
			<div class="carousel-item active">
				<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR8ulHRylkVV1x039Dx1EUIy0lWmlpvGsbkBg&usqp=CAU" class="d-block w-950" alt="...">
			</div>
			<div class="carousel-item">
				<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS6aumGcYjU3j9rCnn3FV62pGutzY9hMPGNVA&usqp=CAU" class="d-block w-100" alt="...">
			</div>
			<div class="carousel-item">
				<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJhyLOVVjoKhD2wO1nQvM2Nyld0-c9REr3zA&usqp=CAU" class="d-block w-100" alt="...">
			</div>
		</div>
		<button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
			<span class="carousel-control-prev-icon" aria-hidden="true"></span>
			<span class="visually-hidden">Previous</span>
		</button>
		<button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
			<span class="carousel-control-next-icon" aria-hidden="true"></span>
			<span class="visually-hidden">Next</span>
		</button>
	</div>



	<section>
		<div class="product">
			<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSW3HiJ-7kMMsU4NS0nMhqtpGuUcp3e6Fiuw&usqp=CAU" alt="Товар 1">
			<h3>Товар 1</h3>
			<p>Описание товара 1.</p>
			<p class="price">Цена: $100</p>
			<button>Добавить в корзину</button>
		</div>
		<div class="product">
			<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSW3HiJ-7kMMsU4NS0nMhqtpGuUcp3e6Fiuw&usqp=CAU" alt="Товар 1">
			<h3>Товар 2</h3>
			<p>Описание товара 2.</p>
			<p class="price">Цена: $100</p>
			<button>Добавить в корзину</button>
		</div>
		<div class="product">
			<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSW3HiJ-7kMMsU4NS0nMhqtpGuUcp3e6Fiuw&usqp=CAU" alt="Товар 1">
			<h3>Товар 3</h3>
			<p>Описание товара 3.</p>
			<p class="price">Цена: $100</p>
			<button>Добавить в корзину</button>
		</div>

		<div class="product">
			<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSW3HiJ-7kMMsU4NS0nMhqtpGuUcp3e6Fiuw&usqp=CAU" alt="Товар 2">
			<h3>Товар 4</h3>
			<p>Описание товара 4.</p>
			<p class="price">Цена: $200</p>
			<button>Добавить в корзину</button>
		</div>
	</section>
	<footer>
		<div class="container">
			<p>© 2023 Stark Indastriz</p>
		</div>
	</footer>

	<script>
		var button = document.getElementById('button');
		var list = document.getElementById('list');

		// Добавляем обработчик клика на кнопку
		button.addEventListener('click', function() {
			// Проверяем состояние списка
			if (list.style.display === 'none') {
				// Если список скрыт, показываем его
				list.style.display = 'block';
			} else {
				// Если список показан, скрываем его
				list.style.display = 'none';
			}
		})

		// Получаем ссылки на кнопку и форму
		document.getElementById('login-btn').addEventListener('click', function() {
			var loginForm = document.getElementById('login-form');
			if (loginForm.style.display === 'none') {
				loginForm.style.display = 'block';
			} else {
				loginForm.style.display = 'none';
			}
		});
		var товар = {
			название: "Новый товар",
			цена: 100,
			количество: 10
		};

		// Функция для добавления товара на страницу
		function добавитьТовар(товар) {
			// Создание элементов для отображения товара
			var блокТовара = document.createElement("div");
			var название = document.createElement("h2");
			var цена = document.createElement("p");
			var количество = document.createElement("p");

			// Задание текстового содержимого элементов
			название.textContent = товар.название;
			цена.textContent = "Цена: " + товар.цена + " руб.";
			количество.textContent = "Количество: " + товар.количество;

			// Добавление элементов в блок товара
			блокТовара.appendChild(название);
			блокТовара.appendChild(цена);
			блокТовара.appendChild(количество);

			// Добавление блока товара на страницу
			var контейнерТоваров = document.getElementById("товары");
			контейнерТоваров.appendChild(блокТовара);
		}

		// Вызов функции для добавления товара
		добавитьТовар(товар);
	</script>

</body></html>
