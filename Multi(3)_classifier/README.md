# Задача на мультиклассовую квалификацию. 

[multi(3)-classes classifier.ipynb](multi(3)-classes classifier.ipynb "notebook.ipynb")


## Описание проекта.

Поставлена задача построения математической модели расчёта потребления электроэнергии на этапе выплавки стали. 


## Навыки и инструменты.

* `python`
* `pandas`  
* `numpy`  
* `seaborn`  
* `os`
* matplotlib `pyplot`
* skimpy `skim`
* scipy.stats `uniform`, `loguniform`
* sklearn.preprocessing `StandardScaler`, `MinMaxScaler`
* imblearn.over_sampling 'RandomOverSampler'
* sklearn.model_selection `GridSearchCV`
* sklearn.model_selection `RandomizedSearchCV`
* sklearn.metrics `roc_auc_score`
* sklearn.metrics `ConfusionMatrixDisplay`
* sklearn.metrics `roc_curve`
* sklearn.linear_model `LogisticRegression`
* sklearn.tree `DecisionTreeClassifier`
* sklearn.ensemble 'RandomForestClassifier', 
* sklearn.ensemble 'GradientBoostingClassifier',
* lightgbm `LGBMClassifier`
* catboost `CatBoostClassifier`
* xgboost.xgb 'XGBClassifier`
* sklearn.ensemble 'StackingClassifier'
* * imblearn.pipeline.`make_imblearn_pipeline`
* sklearn.ensemble 'VotingClassifier


## Общий вывод.

* Провёл исследование и построил математические модели прогностической модели рисков 4 методами.
1. Построил семь моделей c подбором гиперпараметров выбором лучшей в ручном режиме.
2.  По этим 7 моделям создана и обучена StackingClassifier модель.
3.  Создал Pipeline для автоматического расчета 7 моделей.  
4.  Построен ансамбль моделей множественной классификации и провел голосование VotingClassifier для выбора лучшей.
* Для каждой из моделй, полученными этими 4 методама построена 'Матрица ошибок' и построены ROC-кривые (кривые ошибок) для каждого значения риска.
* Выбраны самая лучшая модель.
* Проведена сериализация лучшей прогностической модели.
* Приведён пример чтения модели из файла и расчёта прогноза.


[Вернутся к общему списку проектов](../README.md)