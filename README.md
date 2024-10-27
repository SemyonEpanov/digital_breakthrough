
# Кейс от РЖД: Прогнозирование оттока клиентов

Наш проект решает задачу, поставленную в кейсе цифрового прорыва от РЖД по прогнозированию оттока клиентов компании и понижению спроса на услуги.

## Установка зависимостей
```bash
pip install -r requirements.txt
```
## Описание данных

Изначально нам были даны таблицы выгруженные из 1С по данным о клиентах из разных регионов.

## Схема данных
![Alt text](datachema.jpg)
## Наши шаги по предобработке данных

1. **Data Cleaning and Preprocessing**: We performed data cleaning, handling missing values, and formatting the data for analysis.
2. **Exploratory Data Analysis (EDA)**: We analyzed patterns, distributions, and correlations among key features.
3. **Feature Engineering**: We derived new features to enhance our model’s predictive power.
4. **Modeling and Testing**: We implemented and evaluated several machine learning models to select the best-performing approach.

## Что мы выявили

* **Key Insights**: The analysis revealed that certain user demographics and transaction types are highly correlated with XYZ outcomes.
* **Anomalies**: Identified and resolved significant anomalies that impacted model accuracy.
* **Feature Relevance**: Certain engineered features significantly enhanced the model's performance.

## Наше решение

Our solution addresses the XYZ problem through the following steps:

1. **Data Ingestion**: Load and preprocess data.
2. **Feature Engineering**: Create new features for improved predictive accuracy.
3. **Model Selection**: Train multiple models to determine the most effective approach.
4. **Model Tuning and Evaluation**: Fine-tune the selected model to maximize performance.
5. **Deployment**: Package the final model for deployment in the target environment.

## Использованные технологии
* **Pandas**: Для обработки данных.
* **Matplotlib / Plotly**: Визуализация полученных статистик.
* **Jupyter Notebook**: Интерактивная разработка и тестирование моделей.
* * **Streamlit**: Для хостинга решения и удобного использования.
## Описание файлов

| Нзавание                    | Описание                                                                         |
|------------------------------|---------------------------------------------------------------------------------|
| `requirements.txt`           | Файл с зависимостями проекта               |
| `data_cleaning.py`           | Script for cleaning and preprocessing raw data.                                 |



