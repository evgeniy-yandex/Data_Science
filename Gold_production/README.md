# Повышение эффективности процесса обогащения золота.

[gold_production.ipynb](gold_production.ipynb "notebook.ipynb")


## Описание проекта.

Задача - построить прототип модели машинного обучения для прогнозирования коэффициента восстановления золота из золотосодержащей руды.  
Модель поможет улучшить технологический процесс золотодобывающего горно-обогатительного комбината и снизить производственные издержки.


## Навыки и инструменты.

* `python`
* `pandas`  
* `seaborn`  
* matplotlib.`pyplot`
* skimpy.`skim`
* scipy.stats.`st`
* scipy.stats.`uniform`
* numpy.`random`
* sklearn.preprocessing.`OrdinalEncoder`
* sklearn.preprocessing.`StandardScaler`
* sklearn.preprocessing.`MinMaxScaler`
* sklearn.model_selection.`train_test_split`
* sklearn.model_selection.`GridSearchCV`
* sklearn.model_selection.`RandomizedSearchCV`
* sklearn.model_selection.`cross_val_score`
* sklearn.metrics.`mean_squared_error`
* sklearn.metrics.`mean_absolute_error`
* sklearn.metrics.`make_scorer`
* sklearn.linear_model.`LinearRegression`
* sklearn.tree.`DecisionTreeRegressor`
* sklearn.ensemble.`RandomForestRegressor`
* sklearn.compose.`make_column_transformer`
* sklearn.pipeline.`make_pipeline`
* sklearn.dummy.`DummyRegressor`


## Общий вывод.

* Провёл исследование для стадий флотации, грубой и тонкой очисток с целью построения модели для прогнозирования коэффициента восстановления золота из золотосодержащей руды.
* Построил по три моделей в ручном и автоматическом (с использованием технологии `Pipeline`) режимах. 
* Для золотодобывающего горно-обогатительного комбината рекомендую модель `'Cлучайного леса'`, рассчитанную `Pipeline`.


[Вернутся к общему списку проектов](../README.md)