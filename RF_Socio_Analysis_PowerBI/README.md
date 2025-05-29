# 📊 Социально-экономический анализ по регионам России (2000–2019)

## 🇷🇺 Русская версия

**Описание:**  
Комплексный анализ социально-экономических показателей в городах и регионах России за период с 2000 по 2019 гг. Исследуются такие аспекты, как пенсионное обеспечение, занятость, доходы, демография, здравоохранение, жилищное строительство и образование.

**Данные:**  
- Портал: [data.rcsi.science](https://data.rcsi.science/data-catalog/datasets/187/#dataset-codebook)  
- Дополнительно: собственная структура БД PostgreSQL для анализа

**Технологии:**  
Python (pandas, geopandas), PostgreSQL, Power BI

**Ключевые разделы:**
- Пенсии: региональный анализ, корреляции
- Занятость и зарплата: динамика, зависимости
- Инвестиции и бизнес: количественный рост и связи
- Демография: прирост, рождаемость, смертность, тепловые карты
- Медицина: посещения врачей, койки, дефицит инфраструктуры
- Жильё: финансирование, новые квартиры, связь с обеспечением
- Образование: нагрузка и дефицит мест в школах и детсадах

**Особенности:**
- Визуализация в Power BI
- Использованы методы корреляционного анализа и тепловых карт
- Подчёркнута региональная несбалансированность развития

  **Содержимое репозитория:**
- `RF_Socio_Analysis_PowerBI.pdf` — готовый отчёт с визуализациями Power BI
- `project_db.sql` — структура базы данных (PostgreSQL)
- `data.csv` — сырой датасет
- `russia_full_with_citiesjson` — geoJSON-файл с полигонами городов/регионов (создан для проекта)
- `powerBI data cleaning.ipynb` — скрипт очистки данных
- `csv to postgresSQL.ipynb` — скрипт загрузки в базу
- `sql new tables.txt` — вспомогательные словари
- `create tables.txt` — генерация переменных по типам

---

## 🌍 English Version

**Summary:**  
A comprehensive socio-economic analysis across Russian cities and regions (2000–2019). Focus areas include pensions, employment, income, demographics, healthcare, housing, and education systems.

**Dataset:**  
- Source: [data.rcsi.science](https://data.rcsi.science/data-catalog/datasets/187/#dataset-codebook)  
- Extras: custom PostgreSQL database structure

**Tech stack:**  
Python (pandas, geopandas), PostgreSQL, Power BI

**Main sections:**
- Pensions: regional dynamics and correlation analysis
- Employment and income: growth trends and relationships
- Investment and business: quantitative growth patterns
- Demography: birth/death rates, RNI, heatmap visualizations
- Healthcare: visits, bed count, infrastructure gaps
- Housing: funding correlation, new units, regional patterns
- Education: school and kindergarten capacity vs demand

**Highlights:**
- Power BI dashboards
- Correlation metrics and heatmap analysis

**Repository contents:**
- `RF_Socio_Analysis_PowerBI.pdf` — final analytical report with Power BI visualizations  
- `project_db.sql` — PostgreSQL database schema  
- `data.csv` — raw dataset
- `russia_full_with_citiesjson` — geoJSON file with Russian city and region boundaries (created for project)
- `powerBI data cleaning.ipynb` — data cleaning script in Python
- `csv to postgresSQL.ipynb` — CSV-to-PostgreSQL loading script
- `sql new tables.txt` — SQL for auxiliary dictionaries (dates, OKTMO)
- `create tables.txt` — script to generate variable grouping tables
