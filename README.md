# C. PRO: Что посмотрим? (МТС)
https://official.contest.yandex.ru/contest/79548/problems/C/

Персональная рекомендательная система для видеохостинга с ранжированием топ-10.

## Описание

Система предсказывает топ-10 наиболее релевантных видео для каждого пользователя на основе:
- Истории просмотров
- Демографических данных пользователей
- Метаданных видео (жанры, актеры, режиссеры)

## Запуск

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SergeiLab/video-recommendation-system/blob/main/recommendation_system.ipynb)

1. Нажмите на badge выше
2. Загрузите данные (4 CSV файла)
3. Запустите все ячейки
4. Скачайте результат

## Технологии

- Python 3.14
- LightGBM
- Pandas, NumPy, Scikit-learn
- Google Colab

## Данные

- Пользователи: 198,636
- Видео: 11,856
- Взаимодействия: 754,313

## Метрика

0.5 * (MAP@10 + MAR@10) * 100

## 👤 Автор

Sergei - [GitHub](https://github.com/SergeiLab)

## 📝 Лицензия

MIT
