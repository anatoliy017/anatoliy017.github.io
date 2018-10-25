---
title: Контакты
date: 2018-10-25 14:15:00 +07:00
permalink: contactes
layout: page
---

﻿<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Форма обратной связи на HTML и PHP</title>
	<meta name="robots" content="noindex, nofollow"/>
	<link rel="stylesheet" media="screen" href="styles.css" >
</head>
<body>

            <label for="name">Имя:</label>
            <input type="text"  name="name" placeholder="Введите ваше имя" required />
        </p>
        <p>
            <label for="email">Email:</label>
            <input type="email" name="email" placeholder="Введите электронный адрес" required />
            <span class="form_hint">"name@something.com"</span>
        </p>
        <p>
            <label for="tel">Телефон:</label>
            <input type="tel" name="tel" placeholder="Введите номер телефона" required />
            <span class="form_hint">"+7-123-4567890"</span>
        </p>
        <p>
            <label for="website">Сайт:</label>
            <input type="url" name="website" placeholder="Введите адрес вашего сайта" pattern="(http|https)://.+"/>
            <span class="form_hint">"http://someaddress.com"</span>
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