# ITMO_NLP
NLP tasks of ITMO university course.

## HW1 - Vectorizers, CV, basic text classification
Used cross validations technics and hyperparameters searching, solved task of email spam/not spam classification. As a result got f1-score = 0.95, with some technics.
Tryed Logistic Regression, Multinomial Naive Bayess and Descision Tree Classifier models. The best one on f1 metric became Logistic Regression.

## HW2 - Complex ML models, text classification
In this task we have building makrket products dataset with russian namings and its class. Used preprocessing techniques for namings cleaning and used rubert-tiny (v1 and v2) for getting text emeddings.
In result, got 0.76 accuracy score. It is pretty good result, according to dummy column "Others", which have items that can be more prefferable in other columns, and capture 24% of all dataset.
