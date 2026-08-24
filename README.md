# Проекты по машинному обучению

Коллекция практических проектов по **машинному обучению и анализу данных**.

Основной фокус — исследование данных, проверка гипотез, feature engineering, сравнение моделей и поиск эффективных решений.

---

## Проекты

### 1. Elo Merchant Category Recommendation

**Kaggle · Регрессия · Feature Engineering · Gradient Boosting · Ансамбли**

[Перейти к проекту →](https://github.com/nezdraviy/projects/tree/kaggle_elo_competition)

Решение задачи Kaggle **Elo Merchant Category Recommendation** по прогнозированию лояльности клиентов на основе истории транзакций.

**Использованные подходы:**

* анализ и агрегация транзакционных данных;
* feature engineering;
* XGBoost и LightGBM;
* Lasso;
* feature selection;
* blending моделей.

**Результат:**

| Метрика |       Score |
| ------- | ----------: |
| Public  | **3.78798** |
| Private | **3.68298** |

Финальная модель — ансамбль **XGBoost + LightGBM**.

---

### 2. Used Cars Price Prediction

**Регрессия · EDA · Проверка гипотез · Feature Engineering · CatBoost**

[Перейти к проекту →](https://github.com/nezdraviy/projects/tree/used_cars_research)

Исследование задачи прогнозирования стоимости подержанных автомобилей.

Основной акцент проекта — **формулирование и экспериментальная проверка гипотез**.

В работе сравниваются:

* Ridge;
* Lasso;
* Decision Tree;
* CatBoost.

Используются `GridSearchCV`, RMSE, MAE и R².

В результате экспериментов было показано, что CatBoost после очистки и отбора признаков значительно превосходит рассмотренные альтернативы.

---

## Основные технологии

**Python · pandas · NumPy · scikit-learn · XGBoost · LightGBM · CatBoost · Jupyter · Kaggle**

---

## Подход

Проекты построены вокруг последовательного ML-процесса:

```text
Данные
  ↓
EDA
  ↓
Гипотезы
  ↓
Feature Engineering
  ↓
Baseline
  ↓
Сравнение моделей
  ↓
Оптимизация
  ↓
Оценка результатов
  ↓
Выводы
```

Особое внимание уделяется не только успешным экспериментам, но и **проверке ошибочных гипотез и анализу причин полученных результатов**.

---

## Структура репозитория

Каждый проект находится в отдельной ветке:

```text
main
├── kaggle_elo_competition
└── used_cars_research
```

Подробнее об экспериментах и результатах — в README соответствующих веток.
