🌸 Iris Flower Species Classification using Machine Learning
This project was developed as part of the SystemTron ML Internship – Week 4 Task.

It focuses on classifying Iris flower species into:

Setosa

Versicolor

Virginica

using sepal and petal measurements with a machine learning classification model.

⚙️ Tech Stack
This project uses the following tools and technologies:

Tool	Purpose
Python	Programming language
Pandas	Data handling
NumPy	Numerical operations
Seaborn & Matplotlib	Exploratory Data Analysis and Visualization
Scikit-learn	Model training, evaluation, preprocessing
Joblib	Saving and loading trained models
Google Colab	Development environment

📁 Dataset Overview
The dataset is the classic Iris dataset, which includes:

Sepal Length

Sepal Width

Petal Length

Petal Width
along with the target label: species

✅ Target Variable: species
📊 Number of Classes: 3 (Setosa, Versicolor, Virginica)

🔍 Steps Followed in the Project
📥 1. Installed and Imported Required Libraries
Used Colab to install necessary libraries and import tools for analysis, modeling, and visualization.

📂 2. Uploaded and Loaded the Dataset
Uploaded Iris.csv using Google Colab’s upload widget and loaded it with pandas.

👁️ 3. Initial Data Exploration
Head: Checked first few records

Info: Verified data types and null values

Describe: Statistical summary of numerical columns

🧹 4. Data Cleaning
Dropped irrelevant column Id

Ensured no missing values were present

🧪 5. Outlier Detection (Optional Visualization)
Visualized feature distributions using boxplots

Outliers were not removed to avoid distorting this small dataset

📊 6. Data Visualization
Pairplot: Relationship between features by species

Countplot: Sample count per species

Correlation Heatmap: Understanding inter-feature correlation

🔠 7. Encoded Target Variable
Encoded species using LabelEncoder into numeric format:

Setosa → 0

Versicolor → 1

Virginica → 2

⚖️ 8. Feature Scaling
Used StandardScaler to scale all features for general compatibility (though Random Forest doesn’t require scaling).

🔀 9. Split Dataset
Split into training and test sets with 80/20 ratio and stratified sampling.

🌲 10. Trained the Random Forest Model
Used RandomForestClassifier with 100 trees and max_depth=5

📈 11. Model Evaluation
Evaluated using:

✅ Accuracy

✅ Precision (macro average)

✅ Classification Report

✅ Confusion Matrix (heatmap)

💾 12. Saved the Model
Saved the trained model, label encoder, and scaler using joblib.

🧪 13. Prediction on New Input
Provided a sample input, scaled it, predicted the species, and inverse transformed the label.

🧪 Sample Prediction
python
Copy
Edit
Input: [5.9, 3.0, 5.1, 1.8]
Prediction: Virginica 🌸
👤 Author
Dasari Sai Ram
B.Tech in Civil Engineering
SRKR Engineering College
SystemTron ML Intern – Week 4 Task

🔗 www.systemtron.in

📌 Acknowledgement
This project was created as part of the SystemTron Machine Learning Internship. It helped me understand:

Data preprocessing

Exploratory data analysis

Random forest model training

Evaluation techniques

Model deployment techniques

📄 License
This project is open-source and intended for learning and demonstration purposes only.

