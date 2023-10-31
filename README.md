# Thoridal4_microservices
Thoridal4 microservices repository

## ДЗ №14

- Созданы dockerfile для comment,post и ui
- Собраны образы для сервисов
- Создана bridge-сеть
- Собраны образы на основе Alpine, их докерфайлы пронумерованы
- Создан и подключен docker-volume

## Тесты

```
docker run -d --network=reddit --network-alias=post_db \
--network-alias=comment_db -v reddit_db:/data/db mongo:4

docker run -d --network=reddit \
--network-alias=post thoridal/post:2.0

docker run -d --network=reddit \
--network-alias=comment thoridal/comment:2.0

docker run -d --network=reddit \
-p 9292:9292 thoridal/ui:3.0
```
