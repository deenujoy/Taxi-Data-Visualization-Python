# Taxi Data Visualization Using Python
 
## Project Overview
 
This project demonstrates data cleaning, missing value handling, and data visualization using Python. The analysis is performed on the Seaborn "taxis" dataset to explore trip patterns, fare trends, payment methods, and relationships between key variables.
 
The project utilizes Pandas, Matplotlib, and Seaborn to generate meaningful visual insights from taxi trip data.
 
---
 
## Objectives
 
- Load and explore the taxis dataset.
- Identify and handle missing values.
- Perform data preprocessing.
- Create various visualizations using Matplotlib and Seaborn.
- Understand relationships between fare, distance, payment methods, and boroughs.
 
---
 
## Technologies Used
 
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
 
---
 
## Dataset
 
Dataset Source: Seaborn Built-in Dataset
 
```python
#import seaborn as sns
#df = sns.load_dataset("taxis")

## Data Cleaning
The following preprocessing steps were performed:

Checked for missing values.

Identified numerical and categorical columns.
Imputed numerical columns using median values.
Imputed categorical columns using mode values.
Verified dataset integrity after treatment.
## Visualizations Created

 1. Line Chart
Visualized fare trends over pickup time.
 2. Bar Chart
Compared total fare across pickup boroughs.
 3. Pie Chart
Displayed distribution of payment methods.
### 4. Histogram
Analyzed distribution of trip distances.
### 5. Box Plot
Examined tip distributions across pickup boroughs.
### 6. Count Plot
Counted trips by pickup borough.
### 7. Scatter Plot
Explored relationship between distance and fare.
### 8. Heatmap
Analyzed correlations between numerical features.
### 9. Pair Plot
Visualized pairwise relationships among selected variables.
### 10. Violin Plot
Compared fare distributions across payment methods.

### Key Insights
Fare generally increases with trip distance.
Certain boroughs contribute higher total fares.
Payment methods show varying fare distributions.
Strong positive correlation exists between fare and total amount.
Tip amounts vary across pickup boroughs.

### Project Structure
Plain Text
Taxi-Data-Visualization-Python/
│
├── Taxi_Data_Visualization.ipynb
├── README.md
└── images/
Learning Outcomes

Through this project, I gained hands-on experience in:

### Data Cleaning
Exploratory Data Analysis (EDA)
Data Visualization
Handling Missing Values
Correlation Analysis
Python for Data Analytics

### Author

Deenu Joy

LinkedIn: https://www.linkedin.com/in/deenu-joy-d777

GitHub: https://github.com/deenujoy
