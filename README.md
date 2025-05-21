# Сравнительный анализ алгоритмов градиентного бустинга

**Тема:** "Чем лучше бустить? Тестируем алгоритмы бустинга в бою."

## Цель работы
Провести сравнительный анализ различных алгоритмов градиентного бустинга на практической задаче и определить, какой из них показывает наилучшие результаты.

## Использованные алгоритмы
- sklearn
- XGBoost
- CatBoost
- LightGBM

## Датасет
Для анализа использован датасет [Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn) с Kaggle, содержащий данные об оттоке клиентов телекоммуникационной компании.

## Этапы работы

### 1. EDA (Разведочный анализ данных)
- Загрузка и первичный анализ данных
- Исследование зависимостей между признаками
- Визуализация ключевых характеристик датасета

### 2. Preprocessing & Feature Engineering
- Обработка категориальных переменных с помощью LabelEncoder
- Создание новых признаков
- Разделение данных на обучающую и тестовую выборки

### 3. Сравнение алгоритмов бустинга
- Реализация четырех вариантов градиентного бустинга
- Оценка качества моделей на отложенной выборке
- Настройка гиперпараметров с использованием кросс-валидации
- Финальное сравнение оптимизированных моделей

## Что было сделано
1. Проведён подробный анализ данных телекоммуникационной компании
2. Выполнена предобработка данных и feature engineering
3. Реализованы и настроены 4 варианта градиентного бустинга
4. Проведено сравнение эффективности алгоритмов
5. Определены сильные и слабые стороны каждого подхода

## Выводы
1. Лучшие результаты на данном датасете показал алгоритм [указать какой]
2. Наиболее важными признаками для предсказания оттока оказались [перечислить]
3. Оптимальные гиперпараметры существенно улучшили качество предсказаний
4. [Добавить конкретные метрики и результаты]

## Файлы
- `gradient-boosting-comparison.ipynb` - Jupyter notebook с решением


## Лицензия
MIT License

Copyright (c) 2024 [Ваше имя]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. 