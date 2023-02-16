<br/>
<p align="center">
  <a href="https://github.com/erkutkoral/IBM-ML-SkillUp-Project">
    <img src="https://static.javatpoint.com/tutorial/machine-learning/images/regression-vs-classification-in-machine-learning.png" alt="Logo" width="500" height="200">
  </a>

  <h3 align="center">Classification with Python</h3>

  <p align="center">
    We are going to use the classification algorithms to create a model based on our training data and evaluate our testing data using evaluation metrics.
    <br/>
    <br/>
    <a href="https://github.com/erkutkoral/IBM-ML-SkillUp-Project"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/erkutkoral/IBM-ML-SkillUp-Project/issues">Report Bug</a>
    .
    <a href="https://github.com/erkutkoral/IBM-ML-SkillUp-Project/issues">Request Feature</a>
  </p>
</p>

![Contributors](https://img.shields.io/github/contributors/erkutkoral/IBM-ML-SkillUp-Project?color=dark-green) ![Issues](https://img.shields.io/github/issues/erkutkoral/IBM-ML-SkillUp-Project) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Technologies-Libraries](#technologies-libraries)
* [Roadmap](#roadmap)
* [Authors](#authors)

## About The Project

We will use some of the algorithms taught in the course, specifically:
* Linear Regression
* KNN
* Decision Trees
* Logistic Regression
* SVM

We will evaluate our models using:
* Accuracy Score
* Jaccard Index
* F1-Score
* LogLoss
* Mean Absolute Error
* Mean Squared Error
* R2-Score
Finally, you will use your models to generate the report displaying the accuracy scores.

About The Dataset
The original source of the data is Australian Government's Bureau of Meteorology and the latest data can be gathered from http://www.bom.gov.au/climate/dwo/.

The dataset to be used has extra columns like 'RainToday' and our target is 'RainTomorrow', which was gathered from the Rattle at https://bitbucket.org/kayontoga/rattle/src/master/data/weatherAUS.RData

This dataset contains observations of weather metrics for each day from 2008 to 2017. The weatherAUS.csv dataset includes the following fields:

| Field         | Description                                           | Unit            | Type   |
| ------------- | ----------------------------------------------------- | --------------- | ------ |
| Date          | Date of the Observation in YYYY-MM-DD                 | Date            | object |
| Location      | Location of the Observation                           | Location        | object |
| MinTemp       | Minimum temperature                                   | Celsius         | float  |
| MaxTemp       | Maximum temperature                                   | Celsius         | float  |
| Rainfall      | Amount of rainfall                                    | Millimeters     | float  |
 | Evaporation   | Amount of evaporation                                 | Millimeters     | float  |
 | Sunshine      | Amount of bright sunshine                             | hours           | float  | 
| WindGustDir   | Direction of the strongest gust                       | Compass Points  | object |
| WindGustSpeed | Speed of the strongest gust                           | Kilometers/Hour | object |
| WindDir9am    | Wind direction averaged of 10 minutes prior to 9am    | Compass Points  | object |
| WindDir3pm    | Wind direction averaged of 10 minutes prior to 3pm    | Compass Points  | object |
| WindSpeed9am  | Wind speed averaged of 10 minutes prior to 9am        | Kilometers/Hour | float  |
| WindSpeed3pm  | Wind speed averaged of 10 minutes prior to 3pm        | Kilometers/Hour | float  |
| Humidity9am   | Humidity at 9am                                       | Percent         | float  |
| Humidity3pm   | Humidity at 3pm                                       | Percent         | float  |
| Pressure9am   | Atmospheric pressure reduced to mean sea level at 9am | Hectopascal     | float  |
| Pressure3pm   | Atmospheric pressure reduced to mean sea level at 3pm | Hectopascal     | float  |
| Cloud9am      | Fraction of the sky obscured by cloud at 9am          | Eights          | float  |
| Cloud3pm      | Fraction of the sky obscured by cloud at 3pm          | Eights          | float  |
| Temp9am       | Temperature at 9am                                    | Celsius         | float  |
| Temp3pm       | Temperature at 3pm                                    | Celsius         | float  |
| RainToday     | If there was rain today                               | Yes/No          | object |
| RISK_MM       | Amount of rain tomorrow                               | Millimeters     | float  |
| RainTomorrow  | If there is rain tomorrow                             | Yes/No          | float  |

## Technologies-Libraries

Python with Pandas and Scikit-Learn

## Roadmap

1. Importing Dataset
2. Data Preprocessing
     * Transforming Categorical Variables
     * Training Data and Test Data Split
3. Modeling
4. Evaulating Our Models

## Authors

* **Erkut Koral** - *Industrial Engineering Student* - [LınkedIn](https://www.linkedin.com/in/erkutkoral/)
