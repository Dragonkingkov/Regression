# Graduate Admission Prediction
A machine learning project to predict graduate admission chances based on various academic scores and credentials. The project explores different regression models to find the best predictor for admission probability.


## Dataset Features

- TOEFL Score (Test of English as a Foreign Language)
- University Rating (1-5)
- Statement of Purpose (SOP) Rating (1-5)
- Letter of Recommendation (LOR) Rating (1-5)
- CGPA (Cumulative Grade Point Average)
- Research Experience (0/1)
- Chance of Admit (Target Variable, Range: 0-1)

## Key Findings

Strong correlations discovered between academic scores:

- TOEFL and CGPA: 0.81
- TOEFL and GRE: 0.83
- GRE and CGPA: 0.83
- CGPA is the strongest predictor of admission chances
- Research experience significantly impacts admission probability

GRE Score was dropped due to high multicollinearity
Ridge Regression provided the best results while satisfying linear assumptions

## Data Preprocessing

- Removed unnecessary columns (Serial No.)
- Analyzed correlations between continuous variables
- Handled multicollinearity by dropping GRE scores
- Saved cleaned dataset for modeling



