# Лабораторная работа №4 - Взаимодействие с сервером.
### Выполнила: Торопчина
## Описание
Это приложение позволяет работать с базой данных SQLite в Android. Оно реализует функции добавления, обновления и просмотра записей в базе данных о погоде.

## Структура проекта
1. MainActivity - главная активность приложения, содержащая кнопки для работы с базой данных.
2. SongListActivity - активность для отображения всех записей из базы данных.
3. DatabaseHelper - класс для взаимодействия с базой данных SQLite, включающий методы для добавления, обновления и извлечения данных.
## Функционал
- Просмотр данных - вывод записей о погоде и городе из базы данных на отдельной странице.
- Обновление записи - возможность изменить данные последней записи.
## Особенности
- Переопределен метод onUpgrade для обновления базы данных при изменении версии.
- Применено форматирование для записи температуры добавления записи.
## Установка
1. Склонируйте проект или скачайте исходный код.
2. Откройте проект в Android Studio.
3. Запустите приложение на эмуляторе или физическом устройстве.
## Используемые технологии
Язык программирования: Java
Среда разработки: Android Studio
База данных: SQLite
