## Репозиторий команды ***Стол, стул, чашка***

## Описание

Реализован фановый сервис, который предрставляет веселый тест по профориентации и смешное преобразование над фотографией пользователя путем замены лица представителя професси на его лицо

Ключевая особенность состоит в подмене лиц на двух фотографиях, данная задача решается определенной CV моделью и механизмом взаимодействия с ней, все материалы и код для которых находится в папке **swape_images**

Структура репозитория:

    bob4_bot
    |__ questions_images - картинки для вопросов
    |__ users_images - картинки пользователей
    |__ swap_images - папка с моделью подстановки лица
    |   |__ fotos - картинки профессий
    |   |__ shape_predictor
    |   |__ test_data
    |       |__ images
    |__ main.py - главный файл в котором крутится бот
    |__ createdb.sql - скрипт для создания таблицы в sqlite3
    |__ db.py - оберточные функции для дб
    |__ myHelpers.py - вспомогательные функции
    |--- Далее идёт список обработчиков ---
    |
    |__ menuHandler.py
    |__ gameHandler.py
    |__ imageHandler.py
