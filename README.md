# Домашнее задание к занятию «7.4. Puppeteer 1»

## Решения
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/a34f0c1fac66d7ae133fba25690391c0a6d5eb35/7.4/puppeteer/gh.test.js">gh.test.js</a>. - Автотесты.

<a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/tree/main/7.4/puppeteer">Репозиторий</a> с проектом (Jest+Puppeteer).

## Что было сделано
* В <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.4/puppeteer/package.json">package.json</a> - Дописан скрипт запуска "Jest".
* Создан <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.4/puppeteer/jest.config.js">jest.config.js</a> c настройками об используемых библиотеках.
* Создан <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.4/puppeteer/jest-puppeteer.config.js">jest-puppeteer.config.js</a>.
* Добавлены before/after хуки и тайм-ауты ожидания видимости эелементов страниц, в <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.4/puppeteer/gh.test.js">автотесты</a>.


## Задача 1. Puppeteer timeout

1. Сделайте форк [проекта с лекции](https://github.com/netology-code/jsaqa-code/tree/main/7.4/puppeteer).
2. Исследуйте настройки тайм-аутов и уберите тайм-ауты из конфигурации.
3. Задайте тайм-ауты для каждого из тестов в отдельности.


## Задача 2. Puppeteer before and after hooks

1. Добавьте ещё три теста к существующим и поместите их за блоком `describe`. 
Новые тесты должны проверять заголовки на других страницах приложения.   
3. Существующие хуки не будут подходить для этих тестов, так как новые тесты будут содержать другую стартовую страницу. 
Преобразуйте код так, чтобы всё работало, и соблюдался принцип DRY (Don't Repeat Yourself).
