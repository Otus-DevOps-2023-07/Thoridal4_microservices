# Thoridal4_microservices
Thoridal4 microservices repository

## ДЗ №21

- Изучен kube-dns
- Изучены балансировщики нагрузки
- Установлен ingress controller
- Создан TLS сертификат и использован ingress-secret
- Применена сетевая политика
- Создан том и запрос на его использование подом mongo

## Тесты

```
kubectl apply -f ./kubernetes/reddit -n dev
```
