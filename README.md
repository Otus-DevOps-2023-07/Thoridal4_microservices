# Thoridal4_microservices
Thoridal4 microservices repository

## ДЗ №17

- Создан Dockerfile для поднятия Prometheus
- Сбилжены образы приложений и запушены на dockerhub
- Сконфигурирован node_exporter, mongodb_exporter и blackbox_exporter

## Тесты

```
docker pull thoridal/(список образов: ui, post, comment, prometheus)
docker-compose up -d
```
