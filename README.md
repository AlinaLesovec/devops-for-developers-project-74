# JS Fastify Blog

## Hexlet tests and linter status

![CI](https://github.com/AlinaLesovec/devops-for-developers-project-74/actions/workflows/push.yml/badge.svg)

## Проект: Упаковка в Docker Compose

Блог создан с помощью Fastify с Docker и CI/CD

## Docker Hub

Образ приложения:

liisuu78/devops-for-developers-project-74

## Требования

- Docker
- Docker Compose
- Make

## Использованные технологии

- Fastify — веб-фреймворк
- PostgreSQL — БД
- Caddy — reverse proxy с HTTPS
- Docker — контейнеризация проекта
- GitHub Actions — CI/CD

## Структура проекта

- app/ — исходник приложения
- services/caddy/ — конфиг Caddy
- Dockerfile — разработка
- Dockerfile.production — production
- docker-compose.yml — тесты
- docker-compose.override.yml — разработка

## Установка

```bash
make dev-setup
## Запуск

```bash
make dev
```

Приложение доступно:

http://localhost

https://localhost

## Тесты

```bash
make tests
```
