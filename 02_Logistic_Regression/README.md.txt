**Logistic Regression Project — Predicting Customer Interest**

This project applies a Logistic Regression model to predict whether a client will subscribe to a bank insurance products (y = yes/no) using the Bank Marketing Dataset.

**Project Goal**

The main objectives of this project are:

Clean and preprocess the dataset

Analyze feature distribution and detect outliers

Encode categorical features

Remove multicollinearity using VIF

Standardize numerical features

Train a Logistic Regression classifier

Evaluate the model’s performance using multiple metrics

**Dataset Description**
| Feature            | Description                                                      |
| ------------------ | ---------------------------------------------------------------- |
| **age**            | Age of the client                                                |
| **job**            | Type of job the client has                                       |
| **marital**        | Marital status of the client                                     |
| **education**      | Education level of the client                                    |
| **default**        | Indicates whether the client has credit in default               |
| **housing**        | Indicates whether the client has a housing loan                  |
| **loan**           | Indicates whether the client has a personal loan                 |
| **contact**        | Type of communication used for contacting the client             |
| **month**          | Last contact month of the year                                   |
| **day_of_week**    | Day of the week when the last contact was made                   |
| **duration**       | Duration of the last contact in seconds                          |
| **campaign**       | Number of contacts performed during the current campaign         |
| **pdays**          | Days since the client was contacted in a previous campaign       |
| **previous**       | Number of contacts before the current campaign                   |
| **poutcome**       | Outcome of the previous marketing campaign                       |
| **emp.var.rate**   | Employment variation rate                                        |
| **cons.price.idx** | Consumer price index                                             |
| **cons.conf.idx**  | Consumer confidence index                                        |
| **euribor3m**      | 3-month Euribor interest rate                                    |
| **nr.employed**    | Number of employees in the economy                               |
| **y**              | Target variable: whether the client subscribed to a term deposit |

**Steps Performed**

1. Exploratory Data Analysis (EDA)

Distribution analysis of each feature

Outlier detection and removal

Correlation heatmap

2. Data Preprocessing

Handling missing values (data imputation)

Label encoding for categorical variables

Removing multicollinear features using VIF (Variance Inflation Factor)

Standardization of numerical features

3. Model Building

Train–test split

Logistic Regression model training

**Evaluation Metrics**

The model was evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

ROC Curve & AUC Score

**Techniques Used**

Logistic Regression (scikit-learn)

Train–test split

Standardization (StandardScaler)

VIF for multicollinearity reduction

Data visualization using Seaborn & Matplotlib