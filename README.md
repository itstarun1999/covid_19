
## COVID-19 Project
 This project is focused on predicting the likelihood of an individual being diagnosed with COVID-19 based on various demographic, health, and behavioral factors. The project utilizes three different machine learning algorithms: Decision Tree, Random Forest, and Logistic Regression. The dataset used in this project contains information on individuals who have been diagnosed with COVID-19, including their demographic information and health status.
## Dataset
The dataset used in this project includes the following columns:

#cdc_case_earliest_dt: The earliest date when the case was reported to the Centers for Disease Control and Prevention (CDC).

#cdc_report_dt: The date when the case was reported to the CDC. 

#pos_spec_dt: The date when the specimen was collected for laboratory testing.

#onset_dt: The date when the symptoms of COVID-19 started.

#current_status: The current status of the case (confirmed, probable, suspected, or not reported).

#sex: The gender of the individual.

#age_group: The age group of the individual.

#race_ethnicity_combined: The race and ethnicity of the individual.

#hosp_yn: Whether the individual was hospitalized or not.

#icu_yn: Whether the individual was admitted to an ICU or not.

#death_yn: Whether the individual died or not.

#medcond_yn: Whether the individual had any underlying medical condition or not.
## Machine Learning Algorithms
I have used 3 models here : -Logistic Regression -Decision Tree 
-Random Forest
## Random Forest
Random Forest is an ensemble algorithm that works by constructing multiple Decision Trees and then aggregating the results to make a final prediction. This algorithm helps to reduce the risk of overfitting and improves the accuracy of the prediction. In this project, the Random Forest algorithm was used to build a model to predict the likelihood of an individual being diagnosed with COVID-19.
## Logistic Regression
Logistic Regression is a popular algorithm used for binary classification problems. It works by fitting a logistic curve to the data, which represents the probability of the positive class given the input features. In this project, the Logistic Regression algorithm was used to build a model to predict the likelihood of an individual being diagnosed with COVID-19.
## Conclusion
The COVID-19 Machine Learning Project utilized three different machine learning algorithms to predict the likelihood of an individual being diagnosed with COVID-19 based on various demographic, health, and behavioral factors. The project demonstrated the effectiveness of machine learning algorithms in predicting health outcomes based on real-world data. The project can be extended further by incorporating more features, using more advanced machine learning algorithms, and optimizing the hyperparameters of the models.


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Appendix

Any additional information goes here


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Authors

- [@octokatherine](https://www.github.com/octokatherine)

## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

