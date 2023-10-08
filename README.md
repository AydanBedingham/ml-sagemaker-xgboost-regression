# SageMaker XG-Boost Regression
Jupyter Notebook that uses SageMaker to train an XG-Boost machine learning model. Trains a XG-Boost regression model to predict life expectancy using built-in SageMaker Algorithms. This data was initially obtained from World Health Organization (WHO) and United Nations Website. Data contains features like year, status, life expectancy, adult mortality, infant deaths, percentage of expenditure, alcohol etc.

- Tasks:
    - Split the data into training, vaidation and testing and upload to S3
    - Train a regression model using built-in SageMaker XG-boost algorithm 
    - Assess trained model performance
    - Plot trained model predictions vs. ground truth output
    - Determine the R2 score

- Inputs (Features):
    - YEAR
    - ADULT MORTALITY
    - STATUS
    - INFANT DEATHS
    - ALCOHOL
    - HEPATITIS B

- Outputs:
    - Life Expectancy (Years)
