🚢 Titanic Survival Prediction
This project uses machine learning to predict whether a passenger on the Titanic survived or not, based on features like age, gender, passenger class, and fare. It involves data cleaning, exploratory data analysis (EDA), and model building using logistic regression.

📊 Project Workflow
1. Data Loading and Preprocessing
Dataset: train.csv from the Kaggle Titanic competition

Handled missing values

Converted categorical features (like Sex, Embarked) to numerical values

2. Exploratory Data Analysis (EDA)
Visualized survival distribution by gender, class, and age group using Seaborn

Analyzed correlations between features and survival rates

3. Model Training
Split the data into training and testing sets using train_test_split

Used Logistic Regression to model survival probability

Evaluated the model using accuracy score

🛠️ Technologies Used
Python

NumPy & Pandas

Matplotlib & Seaborn

Scikit-learn (for model building and evaluation)

📁 Dataset Features
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

Sex: Gender

Age: Age in years

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Fare: Passenger fare

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Survived: Survival (0 = No, 1 = Yes)

📈 Results
Model: Logistic Regression

Evaluation metric: Accuracy

Final accuracy achieved: [insert your accuracy here] on the test set
