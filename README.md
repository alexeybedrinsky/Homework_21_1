﻿# Homework_20_2
Задание 1
Создайте новый контроллер и шаблон, которые будут отвечать за отображение отдельной страницы с товаром, на которой необходимо вывести всю информацию о самом товаре.

Задание 2
В созданный ранее шаблон для главной страницы выведите список товаров в цикле. Для единообразия выводимых карточек отображаемое описание необходимо обрезать после первых выведенных 100 символов.

Задание 3
Из-за расширения количества шаблонов появляется слишком много повторяющегося кода, поэтому выделите общий (базовый) шаблон, а также подшаблон с главным меню.

В подшаблон вынесите общие для всех кодовые части (HTML-код). Не забудьте разместить блок с контентом, куда будут вставляться шаблоны, которые используют подшаблон:

{% block content %}

{% endblock %}

И подключите их к другим шаблонам с помощью

{% extends 'путь к базовому шаблону' %}

Код расширенного шаблона разместите внутри блока с контентом.

Задание 4
Для выводимого изображения на странице реализуйте шаблонный фильтр или шаблонный тег, который преобразует переданный путь в полный путь для доступа к медиафайлу.
