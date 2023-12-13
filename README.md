# Thoridal4_microservices
Thoridal4 microservices repository

## ДЗ №18

- Создан compose-файл для системы логирования ElasticSearch + Fluentd + Kibana
- Созданы Dockerfile и конфигурации для Fluentd, выполнена сборка образа
- Выполнен сбор структурированных и не структурированных логов
- Написан grok-шаблон
- Изучен просмотр логов в Kibana
- Изучен просмотр трейсов в Zipkin

## Тесты

```
cd docker && docker-compose -f docker-compose-logging.yml up -d && docker-compose up -d
http://158.160.85.108:9292 - puma
http://158.160.85.108:5601 - Kibana
http://158.160.85.108:9411 - Zipkin
```
