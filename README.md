# Heart-Disease-Prediction
## Introduction
In this project we will evaluate several popular machine learning algorithms such as Logistic Regression, SVC, Decision Tree, KNN, Xgboost, GaussianNB, and Random Forest  & ANN using both Categorical classification & Binary classification to determine which model performs the best in predicting heart disease. The accuracy of each model will be compared, and the results will be presented in an accuracy comparison graph. The main objective of this project is to develop an accurate and reliable machine learning model for heart disease prediction that can assist medical professionals in making timely and accurate diagnoses.

## **Data info:**
The dataset is already provided in the repository (here).

The Cleveland Heart Disease dataset was used for this project. It contains 303 records
of patients, with 14 clinical and non-clinical features. The features are as follows:
1. age: age in years
2. sex: sex (1 = male; 0 = female)
3. cp: chest pain type (1 = typical angina; 2 = atypical angina; 3 = non-anginal pain; 4 =
asymptomatic)
4. trestbps: resting blood pressure (in mm Hg on admission to the hospital)
5. chol: serum cholesterol in mg/dl
6. fbs: fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
7. restecg: resting electrocardiographic results (0 = normal; 1 = having ST-T; 2 =
hypertrophy)
8. thalach: maximum heart rate achieved
9. exang: exercise induced angina (1 = yes; 0 = no)
10. oldpeak: ST depression induced by exercise relative to rest
11. slope: the slope of the peak exercise ST segment (1 = upsloping; 2 = flat; 3 =
downsloping)
12. ca: number of major vessels (0-3) colored by fluoroscopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversible defect
14. target: presence of heart disease (0 = no disease; 1 = disease) 

## **Libraries Used -**
Pandas (for data manipulation)
Matplotlib (for data visualization)
Seaborn (for data visualization)
Scikit-Learn (for data modeling)

## **Contents:**
1. Importing the required libraries.
![15](https://user-images.githubusercontent.com/84839136/231213107-6d36005a-e79e-4f21-a154-e61a70021b6b.png)
2. Importing and Reading the dataset.
3. Exploratory Data Analysis (EDA)
4. Data-Preprocessing
5. Data Visualization
- Correlation Matrix
- Pairplot
- Countplots
![16](https://user-images.githubusercontent.com/84839136/231213375-ed9d4aa4-e4e4-48a0-96ae-ff577039c223.png)
![10 2](https://user-images.githubusercontent.com/84839136/231213561-a59969eb-d06e-403c-87ac-8706d499cd60.png)
6. Data Modeling
- Separating the data into features and target variable.
- Splitting the data into training and test sets.
- Modeling/ Training the data
- Predicting the data
- Calculating the prediction scores
- Getting the model's accuracy
Classification Report
Confusion Matrix
Plotting the confusion matrix
![35](https://user-images.githubusercontent.com/84839136/231213636-598b5654-82ab-4fa8-b550-3fab071c0b12.png)

## **Models Used:**
![WhatsApp Image 2023-04-11 at 9 09 17 PM](https://user-images.githubusercontent.com/84839136/231220246-42802035-239f-4058-8243-e8f723a63344.jpeg)
![WhatsApp Image 2023-04-11 at 9 09 47 PM](https://user-images.githubusercontent.com/84839136/231220309-a7a50687-5567-4039-afb9-5e902ff053b7.jpeg)
![WhatsApp Image 2023-04-11 at 9 10 10 PM](https://user-images.githubusercontent.com/84839136/231220365-e6787a5f-7737-40b0-978f-df18d9f0674e.jpeg)

## **Conclusion:**
In conclusion, we have evaluated multiple machine learning models such as Logistic
Regression, SVC, Decision Tree, KNN, Xgboost, GaussianNB, and Random Forest & ANN using both Categorical classification & Binary classification
for the prediction of heart disease. Our results showed that the Logistic Regression
model achieved the highest accuracy (57.8%), outperforming other models & in ANN, Binary classification achieved more accuracy in comparison to the Categorical classification. The
accuracy comparison graph showed a clear difference in the performance of these
models, with Logistic Regression being the most suitable algorithm for this problem.
