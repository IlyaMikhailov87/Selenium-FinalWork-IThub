## Требования

Docker и Docker Compose

Python 3.10+

pip

Google Chrome и chromedriver

## Запуск OpenCart

OPENCART_PORT=8081 PHPADMIN_PORT=8888 OPENCART_HOST=localhost docker compose up -d

OpenCart будет доступен на: http://localhost:8081

## Создаём и активируем виртуальное окружение

python -m venv venv
source venv/bin/activate 

## Установка зависимостей

pip install -r requirements.txt

## Запуск тестов

pytest
