# Restaurant Data Analysis Project

## 📌 Project Overview

This project focuses on **exploring, cleaning, and analyzing a restaurant dataset** to understand trends in restaurant ratings, cuisines, city-wise distribution, and geographical patterns. The analysis is divided into three major tasks:

1. Data Exploration & Preprocessing
2. Descriptive Analysis
3. Geospatial Analysis

The goal is to generate **meaningful insights** from the data that can help stakeholders understand restaurant performance and customer preferences.

---

## 📂 Dataset Description

The dataset contains information about restaurants, including:

* Restaurant location (City, Country Code, Latitude, Longitude)
* Restaurant attributes (Cuisines, Ratings, etc.)
* Target variable: **Aggregate rating**

---

## ✅ Task 1: Data Exploration and Preprocessing

### 1.1 Dataset Shape

* The dataset was loaded using Pandas.
* The number of **rows and columns** was identified to understand data size.

### 1.2 Missing Values Handling

* Missing values were checked for every column.
* **Numerical columns** were filled using the **median** (robust to outliers).
* **Categorical columns** were filled using the **mode** (most frequent value).

### 1.3 Data Type Conversion

* Data types were reviewed using `df.info()`.
* Columns like **Country Code** were converted to categorical/string type where necessary.

### 1.4 Target Variable Analysis

* The distribution of **Aggregate rating** was visualized.
* Rating imbalance was identified, showing that some rating values appear more frequently than others.

✅ Outcome: A clean, analysis-ready dataset.

---

## ✅ Task 2: Descriptive Analysis

### 2.1 Numerical Statistics

For numerical columns, the following measures were calculated:

* Mean
* Median
* Standard Deviation
* Minimum & Maximum

This helped understand the central tendency and spread of data.

### 2.2 Categorical Variable Distribution

The distribution of these key categorical variables was analyzed:

* **Country Code** – Restaurants distribution across countries
* **City** – Cities with highest restaurant density
* **Cuisines** – Most common cuisines served

### 2.3 Key Findings

* Certain cities dominate the dataset with the highest number of restaurants.
* A small group of cuisines accounts for a majority of restaurants.

✅ Outcome: Clear understanding of popular cities and cuisines.

---

## ✅ Task 3: Geospatial Analysis

### 3.1 Map Visualization

* Restaurants were plotted on an interactive map using **latitude and longitude**.
* Sampling was used to improve performance.

### 3.2 Location-Based Distribution

* Restaurants were analyzed city-wise and country-wise.
* Urban regions showed significantly higher restaurant density.

### 3.3 Location vs Rating Correlation

* Correlation analysis was conducted between:

  * Latitude
  * Longitude
  * Aggregate Rating
* No strong geographical correlation with ratings was observed, indicating that ratings are more dependent on service and food quality than location.

✅ Outcome: Visual and statistical understanding of geographical patterns.

---

## 📊 Final Insights

* Restaurant ratings are **not heavily dependent on geographic location**.
* A few cities and cuisines dominate the restaurant market.
* Data cleaning is crucial for accurate analysis.

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Folium (Geospatial Visualization)
* Jupyter Notebook / VS Code

---

## ▶️ How to Run the Project

1. Place `Dataset .csv` in the project folder.
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn folium
   ```
3. Run the provided Python script or notebook.

---

## 📄 README Summary (For Submission)

This project demonstrates complete **EDA, visualization, and geospatial analysis** on a restaurant dataset. It showcases data preprocessing skills, statistical analysis, and visualization techniques.

