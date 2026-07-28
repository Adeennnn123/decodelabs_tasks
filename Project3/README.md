# Customer Segmentation Using K-Means Clustering

## Project Overview

This Data Science project focuses on customer segmentation using the K-Means Clustering technique. The dataset is analyzed and customers are grouped into different clusters based on their purchasing behavior and other relevant features.

Customer segmentation helps businesses understand different types of customers and develop better data-driven marketing strategies.

## Objectives

* Load and understand the dataset
* Perform data cleaning and preprocessing
* Handle missing values
* Remove duplicate records
* Convert the date column into datetime format
* Create new features from the date column
* Encode categorical data
* Scale numerical features
* Apply Principal Component Analysis (PCA)
* Perform customer segmentation using K-Means Clustering
* Find the optimal number of clusters
* Evaluate the clustering results
* Visualize customer segments

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

### 1. Data Loading

The dataset is loaded using Pandas from an Excel file.

### 2. Data Exploration

The dataset is explored using:

* `head()`
* `tail()`
* `shape`
* `info()`
* `describe()`
* `columns`

### 3. Data Cleaning

The following data cleaning steps are performed:

* Checking missing values
* Checking duplicate records
* Removing duplicate records
* Handling missing values in the dataset

### 4. Feature Engineering

The `Date` column is converted into datetime format.

New features are created from the date column:

* Year
* Month
* Day

### 5. Data Preprocessing

Categorical data is converted into numerical form using Label Encoding.

Numerical features are standardized using `StandardScaler`.

### 6. Dimensionality Reduction

Principal Component Analysis (PCA) is applied to reduce the number of features and make customer segments easier to visualize.

### 7. Customer Segmentation

K-Means Clustering is used to divide customers into different groups based on similarities in their data and behavior.

### 8. Cluster Evaluation

The clustering results are evaluated using the Silhouette Score.

### 9. Data Visualization

Graphs and visualizations are created to understand and compare different customer segments.

## Project Structure

```text
Task3
│
├── project3.ipynb
├── Dataset for Data Analytics.xlsx
└── README.md
```

## Conclusion

The project successfully groups customers into different segments based on their characteristics and behavior. These customer segments can help businesses better understand their customers and make informed, data-driven decisions.

## Author

Adeen Fatima
