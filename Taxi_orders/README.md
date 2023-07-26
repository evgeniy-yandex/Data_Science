# Прогноз количества заказов такси в период пиковой нагрузки.
   
[taxi_orders.ipynb](taxi_orders.ipynb "notebook.ipynb")   


## Описание проекта.

Поставлена задача спрогнозировать количество заказов такси, чтобы привлекать больше водителей в период пиковой нагрузки. 


## Навыки и инструменты.

* `python`  
* `pandas`  
* `numpy`  
* `seaborn`  
* matplotlib.`pyplot`  
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
* statsmodels.tsa.stattools.`adfuller`
* statsmodels.tsa.stattools.`seasonal_decompose`


## Общий вывод.

* Провёл исследование временного ряда с целью выявления трендовых и сезонных закономерностей, случайной составляющей.
* Результаты исследования позволят предсказывать количество заказов такси на следующий час и привлекать больше водителей в период пиковой нагрузки.
* Построил шесть типов моделей. Специалистам сервиса такси для прогнозирования количества заказов рекомендую использовать модель `LGBMRegressor`.


[Вернутся к общему списку проектов](../README.md)