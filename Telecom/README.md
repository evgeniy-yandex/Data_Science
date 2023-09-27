# Определение стоимости автомобилей.

[telecom.ipynb](telecom.ipynb "notebook.ipynb")


## Описание проекта.

Оператор связи хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о клиентах, информацию об их тарифах и договорах.


## Навыки и инструменты.

* `python`
* `pandas`  
* `numpy`  
* `seaborn`  
* `matplotlib`
* `phik`  
* `skimpy`
* sklearn.preprocessing.`OneHotEncoder`
* sklearn.preprocessing.`StandardScaler`
* sklearn.model_selection.`train_test_split`
* sklearn.model_selection.`GridSearchCV`
* sklearn.metrics.`roc_auc_score`, `roc_curve`
* sklearn.linear_model.`LogisticRegression`
* sklearn.tree.`DecisionTreeClassifier`
* sklearn.ensemble.`RandomForestClassifier`
* sklearn.ensemble.`GradientBoostingClassifier`
* lightgbm.`LGBMClassifier`
* catboost.`CatBoostClassifier`
* xgboost.xgb.`XGBClassifier`
* imblearn.pipeline.`make_imblearn_pipeline`
* lightgbm.`plot_importance`
* sklearn.dummy.`DummyRegressor`


## Общий вывод.

Провел исследование с целью построения оптимальной модели определения останется клиент или нет.  

1. Для проведения исследования получены данные по клиентам телекоммуникационной компании и услугам, оказанным им в в период с 2013-10-01 по 2020-02-01.
2. Провёл EDA анализ.
3. Изучил закономерности поведения клиентов.
4. Построил и обучил 7 моделей в 'GridSearchCV'.
5. Построил конвейер pipeline для создания и оценки 7 моделей в 'GridSearchCV':
6. В качестве лучшей определил модель `'GradientBoostingClassifier+Pipeline'` со следующими значениями значения метрик:
    * best_score_ (ROC-AUC): 0.90,
    * ROC-AUC на тестовой выборке: 0.72,
    * время обучения модели: 00:00:06.
7. Провёл анализ важности признаков выбранной модели.
8. Специалистам по продаже автомобилей рекомендую использовать модель `‘GradientBoostingClassifier+Pipeline’`.

[Вернутся к общему списку проектов](../README.md)