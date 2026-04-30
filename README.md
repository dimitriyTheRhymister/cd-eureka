# Eureka Service Discovery Server

Сервер для регистрации всех микросервисов.

## 🔧 Технологии
- Java 21
- Spring Boot 3.2.5
- Spring Cloud Netflix Eureka Server

## 📦 Порт
9009

## 🌐 Доступ
http://localhost:9009

## 📋 Зарегистрированные сервисы

| Сервис | Порт |
|--------|------|
| auth | 9900 |
| desc | 9902 |
| mock | 9912 |
| generator | 9903 |
| notification | 9920 |
| site | 8080 |

## 🧩 Конфигурация
```properties
server.port=9009
eureka.client.fetch-registry=false
eureka.client.register-with-eureka=false