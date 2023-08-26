# Health Insurance Cost Prediction

An end-to-end data science project developed as part of the GlobalAiHub Aygaz Makine Öğrenmesi Bootcamp. The aim is to predict health insurance charges based on various personal attributes. This project encompasses exploratory data analysis, data preprocessing, model selection, hyperparameter optimization, and model evaluation.

## Dataset

The dataset is sourced from Kaggle and can be accessed [here](https://www.kaggle.com/datasets/mirichoi0218/insurance).

### Overview

It consists of the following columns:
- `age`: Age of the individual.
- `sex`: Gender of the individual (male/female).
- `bmi`: Body Mass Index (BMI).
- `children`: Number of children/dependents.
- `smoker`: Smoking status (yes/no).
- `region`: Region in which the individual resides.
- `charges`: Health insurance charges.

## Key Findings from Exploratory Data Analysis

- The distribution of BMI is approximately normal with a significant number of individuals being overweight or obese.
- Smoking is a significant factor in determining health insurance charges. Smokers tend to have higher charges than non-smokers.
- The southeast region has a higher prevalence of smoking and also a slightly higher average BMI.

## Model

The Gradient Boosting Regression model was found to be the most accurate after cross-validation. After hyperparameter optimization, the model achieved the following performance metrics on the test data:
- Root Mean Squared Error (RMSE): 4348.25
- Mean Absolute Error (MAE): 2520.52

## Future Work

- Incorporate additional data sources to improve prediction accuracy.
- Explore deep learning models for further improvement in prediction accuracy.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
