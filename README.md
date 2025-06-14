# Microservice Pipeline
Этот проект демонстрирует конвейер микросервисов:
- Demo Server (FastAPI) генерирует тестовые данные
- Data Requester запрашивает данные и публикует в Kafka
- Data Processor обрабатывает сообщения и публикует в новый топик
- Data Aggregator вычисляет скользящую агрегацию
- DB Loader сохраняет в Postgres
- API Gateway (FastAPI) предоставляет HTTP API для получения данных из Postgres


## Структура проекта
