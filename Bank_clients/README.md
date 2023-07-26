# Прогнозирование оттока клиентов банка.

[bank_clients.ipynb](bank_clients.ipynb "notebook.ipynb")


## Описание проекта.

Предложено построить модель с целью определения Клиентов, которые могут уйти из банка. 


## Навыки и инструменты.

* `python`
* `pandas`  
* `numpy`  
* `seaborn`  
* `matplotlib`  
* fast_ml.model_development.`train_valid_test_split`
* sklearn.model_selection.`GridSearchCV`
* sklearn.metrics.`accuracy_score`
* sklearn.metrics.`recall_score`
* sklearn.metrics.`accuracy_score`
* sklearn.metrics.`precision_score`
* sklearn.metrics.`f1_score`
* sklearn.metrics.`roc_auc_score`
* sklearn.metrics.`roc_curve`
* sklearn.metrics.`confusion_matrix`
* sklearn.metrics.`ConfusionMatrixDisplay`
* sklearn.linear_model.`LinearRegression`
* sklearn.tree.`DecisionTreeClassifier`
* sklearn.tree.`plot_tree`
* sklearn.ensemble.`RandomForestClassifier`
* sklearn.utils.`shuffle`
* imblearn.over_sampling.`SMOTE`
* mblearn.under_sampling.`RandomUnderSampler`
* sklearn.dummy.`DummyRegressor`


## Общий вывод.

* Провёл исследование с целью построения модели прогноза: "Уйдет Клиент из банка или останется".
* Пострил три модели без учёта дисбаланса. Для всех трех моделей применил по 3 метода борьбы с дисбалансом классов.
* Для специалистов банка рекомендую использовать модель `'Случайный лес'` с методом `'Взвешивание классов'`. 
* Результаты исследования позволят специалистам сохранить текущих Клиентов, т.к. это дешевле, чем привлекать новых.


[Вернутся к общему списку проектов](../README.md)