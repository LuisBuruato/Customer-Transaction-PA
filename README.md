📊 Customer Transaction - Predictive Analytics
This project focuses on analyzing customer transaction data to uncover patterns, detect suspicious activity, and build predictive models. The notebook walks through data exploration, visualizations, and machine learning classification using libraries such as pandas, plotly, scikit-learn, and xgboost.

📁 Project Structure
CT Predictive Analytics.ipynb: Main notebook with all analysis steps.

images/: Folder containing exported visualizations.

README.md: This file.

🧠 Project Goals
Perform exploratory data analysis (EDA).

Understand customer behavior and transaction patterns.

Identify potential anomalies or fraudulent transactions.

Train and evaluate machine learning classification models.

Visualize and interpret model results.

📌 Exploratory Data Analysis
Age Distribution by Gender

This chart shows how the age of customers varies across different gender categories.

It helps understand demographic trends in the data.

Feature Correlation Matrix

This heatmap visualizes the correlation between numerical features.

Strong correlations are observed between variables like amount, city_pop, and geographic coordinates.

It guides feature selection for modeling.

Feature Importance

Using an XGBoost model, we rank features by their contribution to prediction.

Features such as amount, city_pop, and job show strong predictive power.

Confusion Matrix

The matrix shows the classification results of the predictive model.

Despite class imbalance, the model performs well in identifying true positives and minimizing false negatives.

⚙️ Machine Learning Modeling
Models used: RandomForestClassifier, XGBClassifier.

Preprocessing includes one-hot encoding, scaling, and train-test split.

Evaluation metrics:

Accuracy

F1-score

Recall

Confusion matrix

✅ Key Takeaways
The data reveals consistent behavioral patterns tied to customer demographics and location.

Predictive modeling with XGBoost proved effective in classifying suspicious transactions.

Geographic and demographic features play a key role in model accuracy.


📬 Contact
Luis Ramón Buruato
🔗 GitHub Profile

Let me know if you’d like this in .md file format or if you need help auto-generating the requirements.txt or a
