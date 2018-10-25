---
title: Контакты
date: 2018-10-25 14:15:00 +07:00
permalink: contactes
layout: page
---


<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Форма обратной связи на HTML и PHP</title>
	<meta name="robots" content="noindex, nofollow"/>
	<link rel="stylesheet" media="screen" href="styles.css" >
</head>
<body>
<h1>Демонстрационная форма для статьи <a href=http://biznessystem.ru/2015/05/html-forma-obratnoj-svyazi-dlya-sajta-php/>HTML форма обратной связи на PHP</a></h1>
<form class="contact_form" action="contact-form.php" method="post">
	<p>
            <label for="name">Имя:</label>
            <input type="text"  name="name" placeholder="Введите ваше имя" required />
        </p>
        <p>
            <label for="email">Email:</label>
            <input type="email" name="email" placeholder="Введите электронный адрес" required />
            <span class="form_hint">Правильный формат "name@something.com"</span>
        </p>
        <p>
            <label for="tel">Телефон:</label>
            <input type="tel" name="tel" placeholder="Введите номер телефона" required />
            <span class="form_hint">Правильный формат "+7-123-4567890"</span>
        </p>
        <p>
            <label for="website">Сайт:</label>
            <input type="url" name="website" placeholder="Введите адрес вашего сайта" pattern="(http|https)://.+"/>
            <span class="form_hint">Правильный формат "http://someaddress.com"</span>
        </p>
        <p>
            <label for="message">Текст сообщения:</label>
            <textarea name="message" cols="40" rows="6" required ></textarea>
        </p>
		<input name="bezspama" type="text" style="display:none" value="" />
        <p>
        	<button class="submit" type="submit">Отправить сообщение</button>
        </p>
</form>
</body>
</html>
/* === Remove input autofocus webkit === */
*:focus {outline: none;}