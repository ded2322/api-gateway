# API-gateway

## Обзор проекта

Это API-gateway позволяющий связать три микросервиса для сайта ХИХИ-ХАХА.


Микросервисы:
- Микросервис отвечающий за регистрацию пользователей: https://github.com/ded2322/auth-microservice.git
- Микросервис отвечающий за загрузку видео: https://github.com/ded2322/upload-microservice.git
- Микросервис отвечающий за показ видео: https://github.com/ded2322/streaming-microservice.git

## Как запустить
1. Клонировать репозиторий
    ```text
    git clone https://github.com/ded2322/api-gateway.git
    ```

2. Перейти в директорию с файлом
    ```text
    cd api-gateway
    ```

3. Изменить в nginx.conf поля upstream на свой IP

4. Собрать и поднять docker-compose
    ```text
     docker-compose up --build 
