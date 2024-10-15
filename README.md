# Traffic Violators Feature Prediction

## I. Introduction

Traffic violations are infractions of vehicle laws committed by drivers. This project focuses on predicting traffic violations using a dataset sourced from Kaggle, which contains various attributes related to traffic offenses. The interest in this subject stems from a fascination with understanding the psychology behind such violations.

## II. Domain-Specific Area: Traffic Rule Violation

Traffic rules are crucial for safety and efficient traffic flow. Factors leading to traffic violations include:

- Increased vehicle numbers
- Poor weather conditions
- Driver inattention
- Reckless behavior

Understanding these factors can help mitigate traffic violations and enhance public safety.

## III. Dataset

The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/shubamsumbria/traffic-violations-dataset), contains 52,966 rows and 15 columns, including:

- `stop_date`: Date of violation
- `stop_time`: Time of violation
- `driver_gender`: Gender of violators (Male-M, Female-F)
- `driver_age`: Age of violators when the violation occurred
- `driver_race`: Race of violators
- `violation`: Type of violation (e.g., Speeding, Moving Violation, Equipment, Registration/Plates, Seat Belt, other)
- `search_conducted`: Whether a search was conducted (True/False)
- `stop_outcome`: Result of the violation
- `is_arrested`: Whether a person was arrested (True/False)
- `stop_duration`: Duration of detention for violators (in minutes)
- `drugsrelatedstop`: Whether the stop was related to drug offenses (True/False)

The dataset's license is unspecified, indicating an "Other" classification.

## IV. Objectives of the Project

The primary goal is to predict traffic violations based on historical data. Specific questions to explore include:

- Times of frequent violations
- Correlation between age and violations
- Racial ratios in relation to violations
- Influence of drugs on violations by age
- Predicting likely violators

## V. Methodology

The project employs regression analysis to develop predictive models, focusing on the relationship between various features and traffic violations. The model's performance is evaluated using accuracy, recall, and Root Mean Square Error (RMSE).

## VI. Results

The findings indicate that speeding and whether a search was conducted are reliable predictors of traffic violations. Additionally:

- Records indicate traffic violations can occur at any age.
- Speeding is the most common type of violation.
- Further investigation into the timing of violations is warranted.

## VII. Conclusion

The developed predictive model serves as a foundation for understanding traffic violations. While the current model demonstrates promising results, future research could focus on refining the questions and enhancing the model's predictive capabilities. The project highlights the potential for using data analysis to improve traffic safety measures.

## VIII. Future Directions

If revisited, the project would benefit from exploring additional features and improving the predictive model. The possibility of using R for better visualization is also worth considering.
