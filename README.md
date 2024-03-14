# Управление книжной библиотекой

Этот проект представляет собой веб-приложение для управления книжной библиотекой. Он позволяет пользователям просматривать, добавлять, обновлять и удалять книги, а также осуществлять поиск книг по различным критериям.

## Основные функции

- Добавление новой книги с указанием заголовка, автора, жанра, года выпуска и других характеристик.
- Просмотр списка всех книг в библиотеке.
- Поиск книг по заголовку, автору, жанру или другим характеристикам.
- Обновление информации о книге (например, изменение автора, жанра или года выпуска).
- Удаление книги из библиотеки.

## Дополнительные функции

- Возможность добавления пользователей и связывание книг с конкретными пользователями.
- Реализация аутентификации и авторизации пользователей.

## Технические детали

- Backend часть приложения написана на Python.
- В качестве базы данных используется [SQLite](https://www.sqlite.org/index.html).
- Реализован REST API с использованием [Flask](https://flask.palletsprojects.com/) для взаимодействия с данными.
- Простой веб-интерфейс создан с использованием HTML, CSS и [Jinja2](https://jinja.palletsprojects.com/) шаблонизатора.

## Установка и запуск

1. Установите зависимости, выполнив следующую команду:
- pip install -r requirements.txt

2. Установите MySQL и создайте базу данных с именем "book".

3. Запустите приложение, выполните:
- python app.py

4. Откройте веб-браузер и перейдите по адресу [http://localhost:5000](http://localhost:5000) для взаимодействия с приложением.