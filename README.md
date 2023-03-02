# Задания ПТИ, Кулагин Н. А.

.body__container {
  font-size: 20px;
  margin: 0 30%;
}

.body__header {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  background-color: #057;
}
.body__header span {
  color: white;
}

.body__header__col {
  -webkit-box-flex: 50%;
      -ms-flex: 50%;
          flex: 50%;
  padding: 5px 0 5px 10px;
}

.body__middle__upper {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  background-color: orange;
  margin: 20px 0 20px 0;
}

.body__middle__upper__col {
  -webkit-box-flex: 50%;
      -ms-flex: 50%;
          flex: 50%;
  padding: 5px 0 5px 10px;
}
.body__middle__upper__col input {
  text-align: center;
}

.body__middle__lower {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}

.body__middle__lower__col {
  -webkit-box-flex: 50%;
      -ms-flex: 50%;
          flex: 50%;
  background-color: #059;
  color: white;
  padding: 10px;
}
.body__middle__lower__col button {
  color: rgba(0, 0, 0, 0);
}

.body__bottom {
  background-color: gray;
  margin: 20px 0 0 0;
  height: 200px;
  color: white;
  text-align: center;
}

<!DOCTYPE html>
<html lang="ru">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Кулагин Н. А. ПИ-С-19</title>
	<link rel="stylesheet" type="text/css" href="css/style.css">
</head>
<body>
	<div class="body__container">
		<form action="#" method="post" enctype="multipart/form-data">
		<div class="body__header">
			<div class="body__header__col">
				<span>Фамилия</span><input type="text" name="sname"><br>
				<span>Имя</span><input type="text" name="fname">
			</div>
			<div class="body__header__col">
				<span>Логин</span><input type="text" name="login"> <br>
				<span>Пароль</span><input type="password" name="passw">
			</div>
		</div>
		<div class="body__middle">
			<div class="body__middle__upper">
				<div class="body__middle__upper__col">
					Выберите время  <br>
					<span><input type="radio" name="r1">9.00 - 10.00<br></span>
					<span><input type="radio" name="r1">10.30 - 11.30<br></span>
					<span><input type="radio" name="r1">12.00 - 13.00<br></span>
					<span><input type="radio" name="r1">14.00 - 15.00<br></span>
					<span><input type="radio" name="r1">15.30 - 16.30<br></span>
					<span><input type="radio" name="r1">17.00 - 18.00<br></span>
				</div>
				<div class="body__middle__upper__col">
					Выберите форму контроля<br>
					<span><input type="checkbox" name="c1">тест<br></span>
					<span><input type="checkbox" name="c2">собеседование<br></span>
					<span><input type="checkbox" name="c3">доклад<br></span>
					<span><input type="checkbox" name="c4">контрольная работа<br></span>
				</div>
			</div>
			<div class="body__middle__lower">
				<div class="body__middle__lower__col">
					Выберите предмет
					<select name="body__middle__lower__col_select">
						<option value="1">Математика</option>
						<option value="2">Физика</option>
						<option value="3">Информатика</option>
						<option value="4">Информационные технологии</option>
					</select>
				</div>
				<div class="body__middle__lower__col">
					Отправить введённые данные <br>
					<button type="submit">Кнопка</button>
				</div>
			</div>
		</div>
		<div class="body__bottom">
			Дополнительная информация <br>
			<textarea name="text"></textarea> <br>
			Кулагин Н. А. ПИ-С-19
		</div>
	</form>
	</div>
</body>
</html>
