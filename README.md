# Dementia Prediction

This project focuses on predicting dementia using machine learning techniques.

## Dataset

The dataset used for this project can be found [here](https://www.kaggle.com/datasets/shashwatwork/dementia-prediction-dataset/data).

## First conclusion

After thorough analysis, it was found that the CDR is a crucial variable. CDR stands for Clinical Dementia Rating and serves as a numeric scale used to quantify the severity of dementia symptoms. The CDR scale ranges from 0 to 3, with the following interpretations:

- CDR 0: No dementia
- CDR 0.5: Very mild dementia (or unsure)
- CDR 1: Mild dementia
- CDR 2: Moderate dementia
- CDR 3: Severe dementia

It's important to note that a model based solely on CDR would likely achieve a high accuracy score, rendering the project redundant. Therefore, a new model will be developed to predict CDR based on other variables. Additionally, the MMSE variable may need to be removed due to similar reasons.

