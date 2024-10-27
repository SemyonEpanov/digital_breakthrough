
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

* **Python**: For data processing, model building, and analysis.
* **Pandas**: For data manipulation.
* **NumPy**: For numerical operations.
* **Matplotlib / Seaborn**: For data visualization.
* **Scikit-Learn**: For implementing machine learning models.
* **Jupyter Notebook**: For documenting analysis and iterative development.
* 
## Описание файлов

| Нзавание                    | Описание                                                                         |
|------------------------------|---------------------------------------------------------------------------------|
| `requirements.txt`           | Lists all dependencies and packages required to run the project.                |
| `data_cleaning.py`           | Script for cleaning and preprocessing raw data.                                 |
| `exploratory_analysis.ipynb` | Notebook with exploratory data analysis and visualizations.                     |
| `feature_engineering.py`     | Script for creating new features from existing data.                            |
| `model_training.py`          | Script for training machine learning models on the processed data.              |
| `model_evaluation.py`        | Contains code for model evaluation metrics and comparison.                      |
| `final_model.pkl`            | Serialized model file ready for deployment.                                     |
| `README.md`                  | Overview of the project, instructions, and file descriptions (this file).       |


