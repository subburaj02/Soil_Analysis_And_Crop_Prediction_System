# Soil_Analysis_And_Crop_Prediction_System
A data analytics and machine learning project that analyzes soil nutrients and environmental factors to recommend the most suitable crop for cultivation.

**🌱 Soil Analysis and Crop Prediction System**
📌 Overview

The Soil Analysis and Crop Prediction System is a machine learning-based project that recommends the most suitable crop based on soil nutrients and environmental conditions.

This project analyzes important soil parameters such as Nitrogen (N), Phosphorus (P), Potassium (K), pH level, along with environmental factors like temperature, humidity, and rainfall to predict the best crop for cultivation.

The goal of this system is to support smart agriculture by helping farmers make data-driven decisions that can improve crop yield and sustainability.

**📁 Dataset**

The dataset used in this project contains 2200 records with different soil and environmental conditions.

Dataset Features
Feature	Description
N	Nitrogen content in soil
P	Phosphorus content in soil
K	Potassium content in soil
temperature	Average temperature (°C)
humidity	Humidity percentage
ph	Soil pH value
rainfall	Rainfall amount (mm)
label	Recommended crop

Example Crops in Dataset

Rice
Maize
Chickpea
Kidney Beans
Banana
Mango
Apple
Coffee
Cotton
Coconut
And many more

**🛠 Tools & Technologies**

Programming: Python

Libraries:
Pandas – Data manipulation
NumPy – Numerical operations
Matplotlib – Data visualization
Seaborn – Statistical visualization
Scikit-Learn – Machine learning models

Environment: Jupyter Notebook

**🔍 Project Workflow**

**1️⃣ Data Loading**

Imported dataset using Pandas
Verified dataset structure and data types
Checked dataset size and columns

**2️⃣ Exploratory Data Analysis (EDA)**

Performed analysis to understand patterns in the data:

Distribution of soil nutrients
Temperature and rainfall analysis
Crop distribution
Correlation between features

Visualization techniques used:

Heatmaps
Distribution plots
Scatter plots
Pair plots

**3️⃣ Data Preprocessing**

Steps performed:

Checked missing values
Verified dataset consistency
Feature selection
Split dataset into training and testing sets

**4️⃣ Machine Learning Model**

A machine learning model was trained to predict the best crop based on soil conditions.

**Steps**

Feature selection
Train-test split
Model training
Model evaluation
Input Parameters

The model takes the following inputs:

Nitrogen (N)
Phosphorus (P)
Potassium (K)
Temperature
Humidity
pH value
Rainfall

**Output**

Recommended crop for cultivation.
🌾 Example Prediction

Input:
N = 90  
P = 42  
K = 43  
Temperature = 20.8  
Humidity = 82  
pH = 6.5  
Rainfall = 202

Output:
Recommended Crop: Rice

**📊 Key Insights**

Soil nutrients N, P, and K play a major role in crop selection.
Environmental factors such as temperature and rainfall significantly impact crop suitability.
Data-driven crop prediction can help farmers improve yield and resource efficiency.

**▶️ How to Run the Project**
Step 1: Install Required Libraries

pip install pandas numpy matplotlib seaborn scikit-learn
Step 2: Open Jupyter Notebook

Run the notebook:
crop_recommendation_using_soil_analysis.ipynb

Step 3: Execute the Cells

Load dataset
Perform EDA
Train machine learning model
Generate crop predictions

**🎯 Skills Demonstrated**

Data Analysis
Exploratory Data Analysis (EDA)
Machine Learning
Data Visualization
Feature Engineering
Agricultural Data Analytics

👨‍💻 Author

Subburaj S
MCA Graduate | Aspiring Data Analyst / Data Scientist

Skills:

Python
SQL
Power BI
Data Analysis
Machine Learning
