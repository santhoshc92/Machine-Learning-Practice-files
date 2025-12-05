**Insurance Charges Prediction — Linear Regression**

This project builds a Linear Regression model to predict medical insurance charges based on various personal, lifestyle, and medical history features.

**The goals of this project are to:**

Explore and understand the Insurance dataset

Perform data cleaning and visualization

Train a Linear Regression model

Evaluate model performance (using R² score)

Predict insurance charges for new inputs

**Dataset Description**

The dataset contains the following features:

| Feature                             | Description                                          |
| ----------------------------------- | ---------------------------------------------------- |
| **age**                             | Age of the individual                                |
| **sex**                             | Gender (male/female)                                 |
| **bmi**                             | Body Mass Index — a measure of body fat              |
| **children**                        | Number of dependents                                 |
| **smoker**                          | Whether the person is a smoker (yes/no)              |
| **Claim_Amount**                    | Previous insurance claim amount filed                |
| **past_consultations**              | Number of past medical consultations                 |
| **num_of_steps**                    | Average number of steps taken daily (activity level) |
| **Hospital_expenditure**            | Previous hospital spending                           |
| **Number_of_past_hospitalizations** | Count of past hospitalizations                       |
| **Annual_Salary**                   | Annual income of the individual                      |
| **region**                          | Residential region                                   |
| **charges** *(Target variable)*     | Total medical insurance charges                      |

**EDA Visualizations**

Distribution of features using distplot

Outlier analysis using boxplots

Correlation analysis via heatmap

**Model Performance**

R² Score: 0.985

**Techniques Used**

Train–test split

Standardization

Linear Regression (scikit-learn)

Data visualization with Seaborn and Matplotlib