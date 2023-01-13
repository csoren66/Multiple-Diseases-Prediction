# Multiple Disease Predictor
![af86a62f-8439-4645-b4d9-71a90e8c78d7](https://user-images.githubusercontent.com/67580321/212327020-285886a1-5571-49be-b0e4-7c3c86d2b43c.png)

## About

This webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:

- Diabetes
- Heart Disease
- Parkinsons Diesease

## Models with their Accuracy of Prediction

| Disease        | Type of Model            | Accuracy |
| -------------- | ------------------------ | -------- |
| Diabetes       | Machine Learning Model   | 77.27%  |
| Heart Disease  | Machine Learning Model   | 81.96%  |
| Parkinsons Disease  | Machine Learning Model   | 87.17%   |

## NOTE

==> Python version 3.9 was used for the whole project.<br>
==> You can find all the models in [Saved model](https://github.com/csoren66/Multiple-Diseases-Prediction/tree/main/Saved%20model) folder.

## Steps to run this application in your system

1. Clone or download the repo.
2. Open command prompt in the downloaded folder.
3. Create a virtual environment

```
mkvirtualenv environment_name
```

4. Install all the dependencies:

```
pip install -r requirements.txt
```

5. Run the application

```
python app.py
```

## Dataset Links

All the datasets were used from kaggle.

- [Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
- [Parkinsons Disease Dataset](https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set)


## Links for Python Notebooks used for model creation

- [Diabetes Notebook](https://github.com/csoren66/Multiple-Diseases-Prediction/blob/main/Notebook/Multiple_disease_prediction_system_diabetes.ipynb)
- [Heart Disease Notebook](https://github.com/csoren66/Multiple-Diseases-Prediction/blob/main/Notebook/Multiple_disease_prediction_system_heart.ipynb)
- [Parkinsons Disease Notebook](https://github.com/csoren66/Multiple-Diseases-Prediction/blob/main/Notebook/Multiple_disease_prediction_system_parkinsons.ipynb)
