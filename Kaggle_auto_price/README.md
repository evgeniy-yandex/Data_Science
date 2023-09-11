# Определение стоимости автомобилей.

[kaggle_auto_price.ipynb](kaggle_auto_price.ipynb "notebook.ipynb")


## Описание проекта.

Требуется построить модель для определения рыночной стоимости автомобиля по данным, содержащим информацию по его производителю, продавцу и номер VIN.  


## Навыки и инструменты.

* `python`
* `pandas`  
* `numpy`  
* `seaborn`  
* `matplotlib`  
* `skimpy`
* `pickle`
* from skimpy import `skim`
* from vininfo import `Vin`
* sklearn.preprocessing.`OrdinalEncoder`
* sklearn.preprocessing.`StandardScaler`
* sklearn.model_selection.`train_test_split`
* sklearn.model_selection.`GridSearchCV`
* sklearn.linear_model.`LinearRegression`
* sklearn.tree.`DecisionTreeRegressor`
* sklearn.ensemble.`RandomForestRegressor`
* sklearn.ensemble.`GradientBoostingRegressor`
* lightgbm.`LGBMRegressor`
* catboost.`CatBoostRegressor`
* xgboost.xgb.`XGBRegressor`
* from sklearn.pipeline import `Pipeline``
* from imblearn.pipeline import make_pipeline as `make_imblearn_pipeline`
* sklearn.dummy.`DummyRegressor`


## Общий вывод.

1. Провел исследование с целью построения оптимальной модели определения рыночной стоимости автомобиля.
2. Создал функцию для расчёта метрики `MAPE`.
3. Построил конвейер `pipeline` для создания и оценки 7 моделей в `GridSearchCV`:  

    - **LinearRegression** - линейная модель.
    - **DecisionTreeRegressor** - линейная модель.
    - **RandomForestRegressor** - ансамблевая модель.
    - **GradientBoostingRegressor** - ансамблевая модель.
    - **LGBMRegressor** - итеративная модель градиентного бустинга.
    - **CatBoostRegressor** - итеративная модель градиентного бустинга.
    - **XGBRFRegressor** - итеративная модель градиентного бустинга.
4. В качестве лучшей в pipeline определили модель `GradientBoostingRegressor` с метрикой на тестовой выборке MAPE = 42.15. 
5. Проверка адекватности модели на константной выборке дала удовлетворительный результат.
6. Специалистам сервиса по продаже автомобилей можно рекомендовать использовать модель `GradientBoostingRegressor`.

[Вернутся к общему списку проектов](../README.md)