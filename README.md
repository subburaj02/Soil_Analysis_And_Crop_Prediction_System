# Soil_Analysis_And_Crop_Prediction_System
A data analytics and machine learning project that analyzes soil nutrients and environmental factors to recommend the most suitable crop for cultivation.

**Soil Analysis and Crop Prediction System**

**Overview**

The Soil Analysis and Crop Prediction System is a machine learning-based project that recommends the most suitable crop based on soil nutrients and environmental conditions.
This project analyzes important soil parameters such as Nitrogen (N), Phosphorus (P), Potassium (K), pH level, along with environmental factors like temperature, humidity, and rainfall to predict the best crop for cultivation.
The goal of this system is to support smart agriculture by helping farmers make data-driven decisions that can improve crop yield and sustainability.

**Dataset**

The dataset used in this project contains 2200 records with different soil and environmental conditions.

**Dataset Features**

1) N - Nitrogen content in soil
2) P - Phosphorus content in soil
3) K - Potassium content in soil
4) temperature - Average temperature (°C)
5) humidity - Humidity percentage
6) ph - Soil pH value
7) rainfall - Rainfall amount (mm)
8) label - Recommended crop
   
**Example Crops in Dataset:**

1)Rice
2)Maize
3)Chickpea
4)Kidney Beans
5)Banana
6)Mango
7)Apple
8)Coffee
9)Cotton
10)Coconut
And many more

**Tools & Technologies**
Programming - Python

**Libraries:**
1)Pandas – Data manipulation
2)NumPy – Numerical operations
3)Matplotlib – Data visualization
4)Seaborn – Statistical visualization
5)Scikit-Learn – Machine learning models

Environment - Jupyter Notebook

**Project Workflow**

**1)Data Loading**

Imported dataset using Pandas
Verified dataset structure and data types
Checked dataset size and columns

**2)Exploratory Data Analysis (EDA)**

Performed analysis to understand patterns in the data:

1)Distribution of soil nutrients
2)Temperature and rainfall analysis
3)Crop distribution
4)Correlation between features

Visualization techniques used:

1)Heatmaps
2)Distribution plots
3)Scatter plots
4)Pair plots

**3)Data Preprocessing**

Steps performed:

1)Checked missing values
2)Verified dataset consistency
3)Feature selection
4)Split dataset into training and testing sets

**4)Machine Learning Model**

A machine learning model was trained to predict the best crop based on soil conditions.

**Steps:**

1)Feature selection
2)Train-test split
3)Model training
4)Model evaluation

**Input Parameters**

The model takes the following inputs:
1)Nitrogen (N)
2)Phosphorus (P)
3)Potassium (K)
4)Temperature
5)Humidity
6)pH value
7)Rainfall

**Output**

Recommended crop for cultivation.

Example Prediction
Input:
N = 90  
P = 42  
K = 43  
Temperature = 20.8  
Humidity = 82  
pH = 6.5  
Rainfall = 202

**Output:**

Recommended Crop: Rice

**Key Insights**

1)Soil nutrients N, P, and K play a major role in crop selection.
2)Environmental factors such as temperature and rainfall significantly impact crop suitability.
3)Data-driven crop prediction can help farmers improve yield and resource efficiency.

**How to Run the Project**

**Step 1: Install Required Libraries**
pip install pandas numpy matplotlib seaborn scikit-learn

**Step 2: Open Jupyter Notebook**
Run the notebook:
crop_recommendation_using_soil_analysis.ipynb

**Step 3: Execute the Cells**
1)Load dataset
2)Perform EDA
3)Train machine learning model
4)Generate crop predictions

**Skills Demonstrated**
1)Data Analysis
2)Exploratory Data Analysis (EDA)
3)Machine Learning
4)Data Visualization
5)Feature Engineering
6)Agricultural Data Analytics

**Author**
Subburaj S 
MCA Graduate | Aspiring Data Analyst 

**Skills:**

1)Python
2)SQL
3)Power BI
4)Data Analysis
5)Machine Learning

