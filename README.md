# Thoridal4_microservices
Thoridal4 microservices repository

## ДЗ №20

- Установлен minikube
- Созданы манифесты деплойментов и сервисов
- Сконфигурированы конфиги доступа к кластеру
- Создан неймспейс dev
- Создан k8s кластер и группа хостов в яндекс облаке
- Приложение развёрнуто в облаке (скриншоты в папке kubernetes)

## Тесты

```
minikube start
kubectl get nodes
kubectl apply -f ./kubernetes/reddit
minikube dashboard
kubectl apply -f ./kubernetes/reddit/dev-namespace.yml
kubectl apply -f ./kubernetes/reddit/ -n dev
```
