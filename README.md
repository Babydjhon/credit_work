# Изучение датасета "Exploring Mental Health Data"

## Тема работы
Изучение датасета "Exploring Mental Health Data", полученного с платформы Kaggle

## Цель работы
Целью работы является исследование датасета с целью нахождения закономерностей, влияющих на развитие депрессии, а также обучение модели для прогнозирования депрессии

## Описание исходных данных
Датасет "Exploring Mental Health Data" был сгенерирован искусственно и содержит информацию о наличии депрессии у людей. В нем представлены различные факторы, которые могут влиять на психическое здоровье, такие как:

- Возраст
- Количество часов, проведённых на работе
- Наличие суицидальных мыслей
- Профессия
- Диета
- Здоровье семьи

## Что делал?

В ходе работы были применены методы машинного обучения для выявления закономерностей в данных. Модель, использованная для анализа, — это **градиентный бустинг**, который обучался на предсказание депрессии

## Полученные результаты
В результате исследования были обнаружены следующие закономерности:
- **Возраст** имеет значительное влияние на вероятность наличия депрессии
- **Наличие суицидальных мыслей** имеет влияние на вероятность наличия депрессии
- Модель **градиентного бустинга** показала хорошие результаты с использованием метрик:
  - **ROC-AUC**: 0.89
  - **Accuracy**: 0.93
  - **Recall**: 0.81
  - **Precision**: 0.85

Эти результаты подтверждают гипотезу о значимости возраста и других факторов в прогнозировании депрессии

## Структура проекта
- `depression.csv` — Данные
- `project_depression.ipynb` — Ноутбук с анализом и моделью
- `README.md` — Описание проекта