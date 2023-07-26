# Классификация текстовых комментариев.

[toxic_comments.ipynb](toxic_comments.ipynb "notebook.ipynb")


## Описание проекта.

Требуется классифицировать текстовые комментарии пользователей с целью выявления токсичных откликов и отправки их на модерацию.


## Навыки и инструменты.

* `python`
* `pandas`  
* `numpy`  
* `seaborn`  
* `matplotlib`  
* `re`
* tqdm.notebook.`tqdm`
* nltk.stem.`WordNetLemmatizer`
* nltk.corpus.`stopwords`
* nltk.corpus.`wordnet`
* sklearn.feature_extraction.text.`TfidfVectorizer`
* sklearn.model_selection.`train_test_split`
* sklearn.model_selection.`GridSearchCV`
* sklearn.metrics.`f1_score`
* sklearn.linear_model.`LogisticRegression`
* sklearn.tree.`DecisionTreeClassifier`
* sklearn.ensemble.`RandomForestRegressor`
* lightgbm.`LGBMClassifier`
* xgboost.xgb.`XGBClassifier`


## Общий вывод.

* Провёл исследование с целью построения модели машинного обучения, которая поможет классифицировать комментарии клиентов интернет-магазина на позитивные и негативные.
* Построил четыре модели. Специалистам интернет-магазин для классифицикации комментариев рекомендую использовать модель `LogisticRegression`.


[Вернутся к общему списку проектов](../README.md)