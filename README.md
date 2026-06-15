
#OIBSIP_DataAnalytics_taskno3
# Cleaning-Data-Project


## 📌 Project Overview

This project focuses on cleaning, preprocessing, and analyzing the Airbnb NYC Listings dataset. The objective is to improve data quality by handling missing values, removing duplicates, treating outliers, and performing exploratory data analysis (EDA) to uncover meaningful insights about Airbnb listings in New York City.

The project demonstrates essential data preprocessing techniques and visualization methods commonly used in real-world data analytics workflows.

---

## 🎯 Objectives

* Understand the structure of the Airbnb NYC dataset.
* Identify and handle missing values.
* Remove duplicate records.
* Detect and treat outliers in pricing data.
* Perform exploratory data analysis using visualizations.
* Generate business insights from cleaned data.
* Export the cleaned dataset for future analysis.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Dataset Information

The dataset contains information about Airbnb listings in New York City, including:

* Listing Name
* Host Information
* Neighborhood Group
* Neighborhood
* Room Type
* Price
* Minimum Nights
* Number of Reviews
* Availability
* Reviews Per Month

---

## 🔄 Data Cleaning Process

The following preprocessing steps were performed:

### 1. Data Inspection

* Examined dataset structure and column information.
* Generated summary statistics.

### 2. Missing Value Treatment

* Identified missing values across columns.
* Filled missing numerical values using median values.
* Replaced missing categorical values with appropriate labels.

### 3. Duplicate Removal

* Detected duplicate records.
* Removed duplicate entries to improve data quality.

### 4. Outlier Detection and Treatment

* Analyzed price distribution.
* Applied the Interquartile Range (IQR) method to identify and remove extreme outliers.

### 5. Data Validation

* Verified dataset consistency after cleaning.
* Confirmed successful preprocessing operations.

---

## 📊 Exploratory Data Analysis

The following visualizations were created:

* Missing Value Analysis
* Room Type Distribution
* Top Neighborhood Analysis
* Price Distribution
* Availability Distribution
* Correlation Heatmap
* Average Price by Room Type

---

## 📈 Key Insights

* Entire homes/apartments generally have higher prices than private rooms.
* Certain neighborhoods contain a significantly higher number of listings.
* Missing values were concentrated in only a few columns.
* Outlier treatment improved the quality of pricing analysis.
* Availability patterns vary considerably across listings.

---

## 📁 Project Structure

```text
Cleaning_Data_Project/
│
├── data.csv
├── cleaned_data.csv
├── Cleaning_Data_Project.ipynb
├── README.md

```

---

## 🚀 How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/yourusername/Airbnb-NYC-Data-Cleaning-EDA.git
```

2. Navigate to the project directory

```bash
cd Airbnb-NYC-Data-Cleaning-EDA
```

3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

4. Open Jupyter Notebook

```bash
jupyter notebook
```

5. Run all cells in the notebook.

---

## 📌 Results

The project successfully transformed raw Airbnb listing data into a clean and analysis-ready dataset. The generated visualizations provide valuable insights into listing distributions, pricing trends, room types, and neighborhood characteristics.

---

## 👨‍💻 Author

**RamCharan S**

Data Analytics Internship
2026

---


