# Тестирование интернет-магазина

[![hexlet-check](https://github.com/ma-us-cyber/qa-engineer-js-from-scratch-project-84/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/ma-us-cyber/qa-engineer-js-from-scratch-project-84/actions)

Протестируйте интернет-магазин, и найдите все ошибки

Учебный проект по ручному тестированию веб-приложений в рамках курса [«Инженер по тестированию» от Хекслета](https://ru.hexlet.io/programs/qa-engineer-js-from-scratch). Цель — протестировать интернет-магазин, найти и описать дефекты, провести регрессионное тестирование.

**Приложение:** Hexlet Products Store — интернет-магазин с каталогом товаров, корзиной, фильтрацией, поиском и оформлением заказа.

**URL:** https://products-store-ru.hexlet.app

**Окружение:** Google Chrome, Windows 11

Учебный проект Хекслета: https://ru.hexlet.io/programs/qa-engineer-js-from-scratch
Как это должно работать: https://products-store-ru.hexlet.app

## Стек

- Ручное функциональное тестирование
- DevTools (Network, Console, Application)
- YAML для описания тестовых артефактов
- GitHub Actions (CI)

## Установка


```bash
git clone https://github.com/ma-us-cyber/qa-engineer-js-from-scratch-project-84.git
cd qa-engineer-js-from-scratch-project-84
```

## Использование

Тестовые артефакты хранятся в YAML-файлах в корне репозитория. Чтобы ознакомиться с результатами:

Откройте requirements.yml — список требований к функциональности магазина.
Откройте test-cases.yml — тест-кейсы с шагами и ожидаемыми результатами.
Откройте testing-report.yml — результаты первого прогона (какие тесты прошли, какие упали).
Откройте bugreports.yml — подробные описания найденных дефектов.
Откройте regress-report.yml — результаты повторного тестирования после исправлений.


---

<details>
<summary>Автоматические тесты Хекслета</summary>

Тесты запускаются на каждый коммит. За запуск отвечает файл `.github/workflows/hexlet-check.yml` — не удаляйте и не переименовывайте ни его, ни репозиторий.

</details>

## О Хекслете

[Хекслет](https://ru.hexlet.io/) — школа программирования: авторские программы обучения с практикой, поддержкой наставников и реальными проектами, которые остаются в резюме. Этот репозиторий — один из таких проектов.
