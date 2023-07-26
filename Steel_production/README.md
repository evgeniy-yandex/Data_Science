# Определение температуры выплавляемой на металлургическом заводе стали

[steel_production.ipynb](steel_production.ipynb "notebook.ipynb")


## Описание проекта.

Поставлена задача построения математической модели расчёта потребления электроэнергии на этапе выплавки стали. 


## Навыки и инструменты.

* `python`
* `pandas`  
* `numpy`  
* `seaborn`  
* `os`
* matplotlib.`pyplot`
* skimpy.`skim`
* skimpy.`clean_columns`
* scipy.stats.`uniform`
* scipy.stats.`loguniform`
* sklearn.preprocessing.`StandardScaler`
* sklearn.preprocessing.`MinMaxScaler`
* sklearn.preprocessing.`PolynomialFeatures`
* sklearn.model_selection.`train_test_split`
* sklearn.model_selection.`GridSearchCV`
* sklearn.model_selection.`cross_val_score`
* sklearn.model_selection.`KFold`
* sklearn.model_selection.`RandomizedSearchCV`
* sklearn.metrics.`mean_absolute_error`
* sklearn.linear_model.`LinearRegression`
* sklearn.tree.`DecisionTreeRegressor`
* sklearn.ensemble.`RandomForestRegressor`
* sklearn.ensemble.`GradientBoostingRegressor`
* lightgbm.`LGBMRegressor`
* lightgbm.`plot_importance`
* catboost.`CatBoostRegressor`
* xgboost.xgb.`XGBRegressor`
* sklearn.dummy.`DummyRegressor`
* sklearn.feature_selection.`RFE`
* imblearn.pipeline.`make_pipeline`


## Общий вывод.

* Провёл исследование и построил математические модели расчёта температуры выплавляемой стали.
* Построил семь моделей c подбором гиперпараметров как в ручном режиме, так и в автоматическом, с технологией `Pipeline` для семи таких же моделей. 
* Выдал рекомендации для улучшения модели.
* Металлургам для контроля расхода электроэнергии в ходе выплавки стали рекомендую использовать модель ‘LGBMRegressor’.


[Вернутся к общему списку проектов](../README.md)