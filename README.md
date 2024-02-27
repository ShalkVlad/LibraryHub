# LibraryHub

LibraryHub - Этот проект представляет собой веб-приложение для управления книгами и авторами в библиотеке. Пользователи могут добавлять новые книги и авторов, а также получать информацию о книгах и авторах, хранящихся в базе данных.

## Функциональность

- Добавление книг и авторов: пользователи могут добавлять новые книги, указывая их название и авторов, а также добавлять новых авторов, указывая их имя и книги, написанные ими.
- Получение информации: пользователи могут получать информацию о книгах и авторах по их идентификаторам.
- Получение списка всех книг и авторов: пользователи могут получать полный список всех книг и авторов, хранящихся в базе данных.

## Использование

1. Установите необходимые зависимости, указанные в файле `requirements.txt`, выполнив команду:
    ```
    pip install -r requirements.txt
    ```
2. Запустите приложение, выполните следующую команду:
    ```
    python app.py
    ```
3. Откройте браузер и перейдите по адресу `http://127.0.0.1:5000/` для доступа к веб-интерфейсу.

## Технологии

- **Фронтенд**: HTML, CSS, JavaScript
- **Бэкенд**: Python, Flask
- **База данных**: В данный момент используется простое хранение в памяти, но для более масштабируемого приложения можно использовать базу данных, такую как SQLite, PostgreSQL или MongoDB.
