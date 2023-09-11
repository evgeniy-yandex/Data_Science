# Определение стоимости автомобилей.

[auto_price.ipynb](auto_price.ipynb "notebook.ipynb")


## Описание проекта.

Требуется построить модель для определения рыночной стоимости автомобиля по данным, содержащим его технические характеристики, особенности комплектации и цены.  


## Навыки и инструменты.

* `python`
* `pandas`  
* `numpy`  
* `seaborn`  
* `matplotlib`  
* `skimpy`
* sklearn.preprocessing.`OrdinalEncoder`
* sklearn.preprocessing.`StandardScaler`
* sklearn.model_selection.`train_test_split`
* sklearn.model_selection.`GridSearchCV`
* sklearn.metrics.`mean_squared_error`
* sklearn.linear_model.`LinearRegression`
* sklearn.tree.`DecisionTreeRegressor`
* sklearn.ensemble.`RandomForestRegressor`
* sklearn.ensemble.`GradientBoostingRegressor`
* lightgbm.`LGBMRegressor`
* lightgbm.`plot_importance`
* catboost.`CatBoostRegressor`
* xgboost.xgb.`XGBRegressor`
* sklearn.dummy.`DummyRegressor`


## Общий вывод.

* Провел исследование с целью построения оптимальной модели определения рыночной стоимости автомобиля.
* Построил семь типов моделей. Специалистам по продаже автомобилей рекомендую использовать модель ‘XGBRegressor’.

[Вернутся к общему списку проектов](../README.md)