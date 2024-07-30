# LOGISTICS DASHBOARD (EN)

The dashboard below is an interactive report focusing on shipment volumes, transit time, carrier status and country distribution. 
There are two more views specifically focusing on: delivered orders and orders in transit. 
The top charts of the dashboard contains the most important KPI’s. 
You can navigate through the dashboard using the menu on the right. 
Each chart shows the most important trends, figures and numbers.

<image src="/Dashboard_2.png" alt="Logistics Dashboard">
  
## GOAL

The purpose of a dashboard is to review the most important KPI’s and results on the one page. 
The dashboard should show the managers how the logistics process performs.  

## METRICS
Metrics focusing on **delivered orders**:
- OTP (On Time Performance - relation of orders delivered on time and total numbers of orders in the period)
- Transit Time - average transit time in a region (light blue area is a range between min and max transit time)
- Total Shipments - number of shipped orders in a period
- Top-10 Countries - the most demanded destination countries  

Metrics focusing on **orders in transit**:
- Current Delivery Status - Orders numbers by delivery status (easy way to find problem orders)
- Carrier Status - Orders numbers by carrier status (more details explanation of current delivery situation)
- Carrier Status by Order Number - the tool to check exact order for status


## PROJECT STEPS
1. Collect row data from different sources (CRM, carriers shipment systems)
2. Join tables and editing format using MS PowerQuery
3. Add support columns and calculate required key performance indicators
4. Create pivot table and related chart for each metric
5. Join all required charts on the board
6. Add timelines and filters

## RESULT
- The dashboard gives on-time delivery performance overview and current status of shipments in transit. Some filters can be applied to choose dates, regions or carriers to review the performance for the past period, provide root cause analysis and find weaknesses in process.
- Monitoring of current order status allows to prevent shipments delay in advance. Inadequate carrier status can be selected and delivery problems might be solved on time.
- Timeline on the charts can be group by weeks, months, years or region. The drill-dawn clearly groups information ranging from the big picture down to individual case.
- By using the dashboard, you will discover the right insights in an easy way. You can apply filters yourself and review different graphs. By immediately having the right information available, correct decisions can be made.

-----
-----

# Дашборд для Логистики (RU)
Дашборд ниже представляет собой интерактивный отчет, сосредоточенный на объемах отправок, времени доставки, статусе перевозчика и распределении заказов по странам. 
Метрики, отраженные в отчетах, фокусируются на двух основных направлениях: **доставленных заказах** и **заказах в пути**. 
Верхние графики содержат самые важные ключевые показатели (KPI). Вы можете перемещаться по панели, используя меню справа. 
Каждая диаграмма показывает наиболее важные тренды, цифры и показатели.

## ЦЕЛЬ
Цель создания дашборда заключается в том, чтобы на одной странице отобразить самые важные ключевые показатели и результаты. 
Панель должна показать менеджерам, как работает процесс логистики.

## МЕТРИКИ
Метрики, фокусирующиеся на доставленных заказах:
- OTP (On Time Performance — отношение заказов, доставленных вовремя, к общему числу заказов за период)
- Transit Time (Время доставки) — среднее время доставки по региону (светло-голубая область — диапазон между минимальным и максимальным временем доставки)
- Total Shipments (Общее количество отгрузок) — количество отправленных заказов за период
- Top-10 Countries (Топ-10 стран) — самые востребованные страны назначения

Метрики, фокусирующиеся на заказах в пути:
- Current Delivery Status (Текущий статус доставки) — количество заказов по статусу доставки (удобный способ найти проблемные заказы)
- Carrier Status (Статус перевозчика) — количество заказов по статусу перевозчика (подробное объяснение текущей ситуации с доставкой)
- Carrier Status by Order Number (Статус перевозчика по номеру заказа) — инструмент для проверки точного статуса заказа

## ЭТАПЫ ПРОЕКТА
1. Сбор необработанных данных из разных источников (CRM, системы отправки перевозчиков)
2. Объединение таблиц и редактирование формата с использованием MS PowerQuery
3. Добавление вспомогательных столбцов и расчет необходимых ключевых показателей
4. Создание сводной таблицы и соответствующей диаграммы для каждой метрики
5. Объединение всех необходимых диаграмм на дашборде
6. Добавление временных шкал и фильтров

## РЕЗУЛЬТАТ
- Дашборд предоставляет обзор выполнения доставок заказов в срок и текущего статуса отгрузок в пути. 
- Есть фильтры для выбора дат, регионов или перевозчиков для анализа производительности за прошлый период, проведения анализа первопричин и выявления слабых мест в процессе.
- Мониторинг текущего статуса заказов позволяет предотвратить задержки отправок заранее. Сомнительный статус перевозчика можно выявить, и проблемы с доставкой могут быть решены вовремя.
- Временная шкала на диаграммах может группироваться по неделям, месяцам или годам, есть фильтр по регионам. Детализированный анализ четко группирует информацию от общей картины до отдельных случаев.
- Используя дашборд выше, можно легко обнаружить правильные инсайты, самостоятельно применять фильтры и просматривать различные графики. Имея доступ к правильной информации, можно принимать правильные решения вовремя.
