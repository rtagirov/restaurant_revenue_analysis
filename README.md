# Анализ ресторанной выручки и BI-дашборды

Tableau Public:  
https://public.tableau.com/app/profile/rinat.tagirov4764/viz/restaurant_revenue_dashboards/Executive1

## Описание проекта

Проект представляет собой полноценную систему аналитики ресторанной выручки на основе транзакционных данных за февраль 2025 и февраль 2026 годов.

Цель проекта — преобразовать сырые чековые данные в аналитические витрины и интерактивные BI-дашборды, отвечающие на ключевые бизнес-вопросы:

- как меняется выручка;
- выполняется ли план;
- какие каналы формируют продажи;
- как меняется загрузка ресторана;
- какие блюда продаются лучше всего;
- как анализировать поведение гостей через чековые метрики.

Проект включает:
- подготовку данных;
- аналитическое моделирование;
- визуализацию данных в Tableau.

---

# Этапы проекта

## 1. Подготовка данных

Сырые транзакционные данные были очищены и преобразованы с помощью:
- Pandas;
- SQL.

Гранулярность исходных данных:

1 строка = 1 блюдо внутри чека

Для разных бизнес-задач были созданы отдельные аналитические витрины.

---

## 2. Аналитическое моделирование

Были построены аналитические слои для:
- KPI;
- анализа каналов;
- операционного анализа;
- анализа продуктов;
- анализа поведения гостей;
- анализа план/факт.

---

## 3. Разработка дашбордов

В Tableau были разработаны интерактивные дашборды:

### Общий обзор
- KPI выручки;
- выполнение плана;
- сравнение годов;
- накопительная выручка.

### Анализ каналов
- выручка по каналам;
- доля каналов;
- средний чек;
- сравнение каналов год к году.

### Время и загрузка
- почасовая выручка;
- количество чеков;
- тепловые карты;
- длительность визитов;
- декомпозиция выручки.

### Продукт
- декомпозиция изменения выручки по категориям
- классификация изменения выручки по категориям

---

# Назначение проекта

Проект демонстрирует построение BI-аналитики для ресторанного бизнеса:
- контроль выручки;
- анализ каналов продаж;
- анализ загрузки;
- контроль выполнения плана;
- анализ продуктов;
- визуализация ключевых бизнес-метрик.

================================================================================

# Restaurant Revenue Analysis & BI Dashboards

Tableau Public:  
https://public.tableau.com/app/profile/rinat.tagirov4764/viz/restaurant_revenue_dashboards/Executive1

## Project Overview

This project is a complete restaurant revenue analytics and business intelligence system built using transactional restaurant data for February 2025 and February 2026.

The goal of the project is to transform raw check-level data into analytical data marts and interactive BI dashboards answering key business questions:

- how revenue changes over time;
- whether the sales plan is achieved;
- which channels generate revenue;
- how restaurant workload changes;
- which products perform best;
- how guest behavior can be analyzed through check-based metrics.

The project includes:
- data preparation;
- analytical modeling;
- Tableau visualization.

---

# Project Stages

## 1. Data Preparation

Raw transactional restaurant data was cleaned and transformed using:
- Pandas;
- SQL.

Source data granularity:

1 row = 1 dish inside 1 check

Separate analytical tables were created for different business tasks.

---

## 2. Analytical Modeling
Several analytical layers were built for:
- executive KPIs;
- channel analysis;
- operational analysis;
- product analytics;
- guest behavior analysis;
- plan vs fact analysis.

---

## 3. Dashboard Development

Interactive Tableau dashboards were developed for:

### Executive Dashboard
- revenue KPIs;
- plan completion;
- year-over-year comparison;
- cumulative revenue analysis.

### Channel Analysis Dashboard
- revenue by channel;
- revenue share;
- average order value;
- year-over-year channel comparison.

### Time & Operations Dashboard
- hourly revenue;
- check dynamics;
- heatmaps;
- visit duration analysis;
- revenue decomposition.

### Product
- revenue change decomposition
- revenue change classification

---

# Goal

The project demonstrates the development of BI analytics system for restaurant business including:
- revenue monitoring;
- sales channel analysis;
- operational analytics;
- plan monitoring;
- product analytics;
- business metric visualization.
