# Credit Card Fraud Data: Exploratory Analysis

[English](#english) | [Русский](#русский)

## English

Exploratory data analysis of a Kaggle credit-card transaction dataset. The notebook examines class imbalance, feature distributions, group differences, relationships between transaction signals, missing values, and outliers.

### Notebook

- `credit_card_fraud_eda.ipynb` — analysis and visualizations.

### Dataset

The notebook uses the [Credit Card Fraud Detection 2026 dataset on Kaggle](https://www.kaggle.com/datasets/uditjain13/credit-card-fraud-detection-2026). The CSV is not included in this repository; the notebook downloads it with `kagglehub`.

### Run

Install the notebook dependencies:

```bash
python -m pip install numpy pandas matplotlib seaborn kagglehub jupyter
```

Open the notebook in Jupyter or Kaggle. In a local environment, make sure the CSV path in the loading cell points to the directory returned by `kagglehub.dataset_download`.

### Topics

- Class balance and descriptive statistics
- Transaction amount, customer age, distance, payment channel, and authentication features
- Fraud vs. non-fraud group comparisons
- Correlation and category cross-tabulations
- Missing-value and IQR-based outlier exercises

## Русский

Учебный исследовательский анализ набора транзакций по кредитным картам с Kaggle. Ноутбук изучает дисбаланс классов, распределения признаков, различия между группами, связи между параметрами транзакций, пропуски и выбросы.

### Ноутбук

- `credit_card_fraud_eda.ipynb` — анализ и визуализации.

### Данные

Используется [набор Credit Card Fraud Detection 2026 на Kaggle](https://www.kaggle.com/datasets/uditjain13/credit-card-fraud-detection-2026). CSV-файл в репозиторий не включён; ноутбук загружает его через `kagglehub`.

### Запуск

Установите зависимости:

```bash
python -m pip install numpy pandas matplotlib seaborn kagglehub jupyter
```

Откройте ноутбук в Jupyter или Kaggle. При локальном запуске убедитесь, что путь в ячейке чтения данных указывает на каталог, возвращённый `kagglehub.dataset_download`.

### Темы

- Баланс классов и описательная статистика
- Сумма транзакции, возраст, расстояние, канал оплаты и способ аутентификации
- Сравнение мошеннических и обычных транзакций
- Корреляции и таблицы сопряжённости категориальных признаков
- Практика обработки пропусков и поиска выбросов методом IQR
