# ЧАЙНЫЙ ДОМ INC. 🌿

Небольшое приложение с возможностью добавлять информацию о сортах чая в каталог и на карту. 

`Стэк:` HBS, Express.JS + MongoDB, API Яндекс.Карты.

## Для запуска проекта

- Склонировать проект
- Инициализировать проект - npm i
- Запустить проект - node app.js
- Для запуска приложения используется база MongoDB
- Сервер запустится по адресу localhost:3000

### Возможности приложения

- Авторизация как администратор* или пользователь
- Регистрация пользователя
- Информация о чае добавляется на карту по названию города или страны (Яндекс Геокодер)

### Администратор

- Просмотр информации о чае в каталоге и на карте
- Добавление карточки с чаем
- Добавление изображения чая
- Добавление комментария к карточке чая
- Удаление карточки с чаем

### Пользователь

- Просмотр информации о чае в каталоге и на карте
- Добавление комментария к карточке чая

*Для того чтобы назначить администратора:
- Найти в базе нужного юзера и установить в его моделе admin: true

# Preview проекта

![screenshot](Desktop-1610313986241.gif)

### `Авторы проекта`

- Views, Routes - [Игорь Волков](https://github.com/gavriil-volkov), [Ольга Гордеева](https://github.com/OlgaGordeeva-Al)
- Работа с Яндекс API - [Андрей Коваленко](https://github.com/andrewcova)
- Верстка - [Игорь Волков](https://github.com/gavriil-volkov)
