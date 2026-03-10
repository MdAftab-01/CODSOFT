📊 Titanic Survival Prediction Project

🎯 Project Objective
➡️ The objective of this project was to analyze the Titanic dataset and build a machine learning model to predict whether a passenger survived (1) or did not survive (0).

🔹 Step-by-Step Project Workflow
📂 1. Data Collection

📥 Loaded the Titanic dataset containing passenger details such as:
Age
Gender
Passenger Class
Fare
Embarked Port
Survival Status

➡️ Dataset Size: 891 passengers

🧹 2. Data Cleaning

⚙️ Performed preprocessing to prepare the dataset for machine learning.

✔ Removed unnecessary columns:
PassengerId
Name
Ticket
Cabin

✔ Handled missing values:
Age → Filled using median
Embarked → Filled using mode
➡️ Ensured the dataset contained no null values.

📊 3. Exploratory Data Analysis (EDA)

📈 Analyzed survival patterns using visualizations.

Key findings:
👩 Female passengers had higher survival rates
🚢 1st class passengers survived more than 3rd class
👶 Younger passengers had better survival chances
💰 Passengers with higher fares were more likely to survive

🔄 4. Feature Engineering
Converted categorical variables into numeric format.
✔ Gender Encoding
Male → 0
Female → 1
✔ Applied One-Hot Encoding for the Embarked column.
➡️ This allowed the machine learning model to process the data.

🧠 5. Model Building
Used Logistic Regression to build a classification model.
Steps performed:
✔ Feature & Target Separation
✔ Train-Test Split (80% training, 20% testing)
✔ Model Training

📊 6. Model Evaluation
Evaluated the model using:
✔ Accuracy Score
✔ Confusion Matrix
✔ Classification Report

📈 Model Accuracy:
➡️ 81%

📉 Confusion Matrix Results
✔ Model correctly predicted 90 passengers did not survive
✔ Model incorrectly predicted 15 passengers survived when they did not
✔ Model incorrectly predicted 19 passengers did not survive but they actually survived
✔ Model correctly predicted 55 passengers survived

🏆 Final Conclusion
✔ Built a machine learning model to predict passenger survival
✔ Performed data cleaning, feature engineering, and exploratory analysis
✔ Logistic Regression model achieved 81% accuracy
✔ Demonstrated how passenger characteristics influence survival probability

🛠 Tools & Technologies Used
🐍 Python
📊 Pandas & NumPy
📈 Matplotlib & Seaborn
🤖 Scikit-Learn

🚀 Skills Demonstrated
✔ Data Cleaning
✔ Exploratory Data Analysis
✔ Feature Engineering
✔ Machine Learning
✔ Model Evaluation
