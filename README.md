Данный проект представляет собой небольшое учебное backend API
и реализует несколько простых операций:

- загрузка, обновление и удаление "файлов" и "категорий"
- предоставление информации о них по запросу

Преполагается развертывание сервера при помощи фреймворка FastAPI
в docker-контейнере на удаленной машине ubuntu.

В качестве СУБД используется Postgresql. 

Для запуска приложения используется сервер ASGI Uvicorn.

