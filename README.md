# Project "Store"

This README file provides information about the "Store" project. Below, you'll find a description of the project, its dependencies, and additional notes.

## Project Description

The **Store** project is a web application based on Django, designed for managing an online store. It utilizes various Django packages and interacts with PostgreSQL as its database. The project includes features such as user authentication, debugging, and API development.

## Project Structure

The project has the following structure:

- `store`: Root directory of the Django project.
- `poetry.lock`: Poetry's lock file to ensure consistent dependency versions.
- `pyproject.toml`: Poetry configuration file, specifying project metadata and dependencies.
- `README.md`: Project documentation.

## Dependencies

The project uses the following Python packages managed by [Poetry](https://python-poetry.org/):

- **Django** (^4.2.6): Web framework for building robust web applications.
- **Pillow** (^10.0.1): Python Imaging Library (PIL) fork for image processing.
- **django-allauth** (^0.57.0): Authentication, registration, and account management for Django.
- **django-debug-toolbar** (^4.2.0): A set of panels displaying various debug information about the current request/response.
- **django-environ** (^0.11.2): Environment configuration for Django applications.
- **django-extensions** (^3.2.3): Useful extensions for Django.
- **djangorestframework** (^3.14.0): Powerful and flexible toolkit for building Web APIs.
- **psycopg2** (^2.9.8): PostgreSQL adapter for Python.
- **django-redis** (^5.4.0): Redis integration for Django.
- **redis** (^4.6.0): Python client for Redis.
- **celery** (^5.3.4): Distributed task queue for Django.
- **stripe** (^6.6.0): Python client for the Stripe API.

## Additional Dependencies

- **PostgreSQL**: Database backend for storing application data.

## Development Dependencies

The following tools are used for development purposes:

- **flake8** (^6.1.0): A tool for linting and static analysis of Python code.
- **isort** (^5.12.0): A tool for sorting Python imports.


# Проект "Store"

Этот файл README предоставляет информацию о проекте "Store". Ниже вы найдете описание проекта, его зависимости и дополнительные заметки.

## Описание проекта

Проект "Store" - это веб-приложение, основанное на Django и предназначенное для управления онлайн-магазином. Он использует различные пакеты Django и взаимодействует с PostgreSQL в качестве базы данных. Проект также включает функции аутентификации пользователей, отладки и разработки API.

## Структура проекта

Проект имеет следующую структуру:

- `store`: Корневая директория Django-проекта.
- `poetry.lock`: Файл блокировки зависимостей Poetry для обеспечения согласованных версий.
- `pyproject.toml`: Файл конфигурации Poetry, определяющий метаданные проекта и зависимости.
- `README.md`: Документация проекта.

## Зависимости

Проект использует следующие пакеты Python, управлением [Poetry](https://python-poetry.org/):

- **Django** (^4.2.6): Веб-фреймворк для создания надежных веб-приложений.
- **Pillow** (^10.0.1): Форк библиотеки Python Imaging Library (PIL) для обработки изображений.
- **django-allauth** (^0.57.0): Аутентификация, регистрация и управление учетными записями для Django.
- **django-debug-toolbar** (^4.2.0): Набор панелей, отображающих различную отладочную информацию о текущем запросе/ответе.
- **django-environ** (^0.11.2): Конфигурация окружения для приложений Django.
- **django-extensions** (^3.2.3): Полезные расширения для Django.
- **djangorestframework** (^3.14.0): Мощный и гибкий инструментарий для создания веб-API.
- **psycopg2** (^2.9.8): Адаптер PostgreSQL для Python.
- **django-redis** (^5.4.0): Интеграция Redis для Django.
- **redis** (^4.6.0): Клиент Redis для Python.
- **celery** (^5.3.4): Распределенная очередь задач для Django.
- **stripe** (^6.6.0): Клиент Stripe API для Python.

## Дополнительные зависимости

- **PostgreSQL**: База данных для хранения данных приложения.

## Зависимости разработки

Для целей разработки используются следующие инструменты:

- **flake8** (^6.1.0): Инструмент для линтинга и статического анализа кода Python.
- **isort** (^5.12.0): Инструмент для сортировки импортов Python.
