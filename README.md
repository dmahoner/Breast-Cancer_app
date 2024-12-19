# Prediction of Breast Cancer Recurrence with Machine Learning
Dominique Mahoner (team lead), Bucknell University; Jude Okolie (professor), Bucknell University. 
# Background
The Breast Cancer Recurrence Prediction App is a machine learning-powered tool designed to assist healthcare professionals in predicting the likelihood of a breast cancer recurrence. This app levereages patient data and advanced predictive models in order for the app to support clinical decision-making and personalized treatment planning.

# Input Variables (Features)
The model uses the following patient-specific input variables:
- Age Range: Categorical variable representing the patient's age group (e.g., "20-29", "30-39").
- Menopausal Status: Whether the patient is pre-menopausal or post-menopausal.
- Tumor Size Range: Range of the tumor size in millimeters (e.g., "0-2", "3-5").
- Invasive Nodes Size: Size of invasive lymph nodes (e.g., "0-4", "5-9").
- Node Capsule Stage: Presence or absence of a node capsule ("Capsule Present" or "Capsule Absent").
- Degree of Malignancy: Numerical representation of tumor malignancy (1: Low, 3: High).
- Breast Side: The side of the breast affected (Left or Right).
- Breast Quadrant: Tumor location within the breast (e.g., "Upper Outer Quadrant", "Central").
- Irradiation Status: Whether the patient underwent radiation therapy (Yes or No).

# Output Variable (Target)
The model predicts the recurrence status of breast cancer:
- 1: Recurrence (Yes)
- 0: No Recurrence (No)

## Project Goals
This app contains the following steps: 
1. Data Preprocessing: Handles missing data, scales numerical values, and encodes categorical variables to prepare patient data for analysis.
2. Predictive Modeling:  Utilizes machine learning models to predict cancer recurrence with high accuracy. (final chosen model is SVM)
3. Feature Importance Analysis: Identifies key factors contributing to recurrence risk for accurate results.
4. Visualization Tools: In order to help understnad model predictions the following visualization tools were used; partial dependence plots and bee swarm plots.

## Exploratory Data
# Heat Map
![image](https://github.com/user-attachments/assets/18478ce3-69c3-4953-9801-296ecf1a971a)


# Machine Learning Models
This app initially is trained on 5 supervised learning models: 
- Random Forest
- Support Vector Machine
- Gradient Boosting
- K-Nearest Neighbors
- Linear Regression
These models use the nine previously listed features to predict whether or not a reccurence will happen.

# Model performance

![image](https://github.com/user-attachments/assets/05579786-62f1-496c-9b62-83e836e81a26)

## Ethics
- Deon's checklist: https://huggingface.co/spaces/dmahoner/Cancer-Recurrence_Deon_Checklist
- Ethic Data card: https://huggingface.co/spaces/dmahoner/Cancer-Recurrence_Data_Card?logs=container

## Graphical USer Interface
![image](https://github.com/user-attachments/assets/fa3cd459-1c03-43f7-84ea-542076cba604)


## Future Implementations
1. Regular updates

