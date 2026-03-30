# 🎬 Netflix Data Analysis using Python (Pandas)

## 📌 Project Overview  
This project performs an exploratory data analysis (EDA) on Netflix datasets to understand content characteristics and viewer engagement patterns. The analysis combines two datasets containing title information and user engagement metrics to uncover relationships between variables such as genre, duration, release year, and popularity.

The goal is to transform raw data into meaningful insights using Python and data visualisation techniques.

---

## 🎯 Objectives  

- Analyse how viewer engagement varies across different Netflix titles  
- Explore relationships between content characteristics (genre, duration, release year) and popularity  
- Identify patterns in content growth and audience behaviour  
- Perform data cleaning, transformation, and feature engineering for analysis  

---

## 🛠️ Technologies Used  

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 📂 Project Structure  
# 🎬 Netflix Data Analysis using Python (Pandas)

## 📌 Project Overview  
This project performs an exploratory data analysis (EDA) on Netflix datasets to understand content characteristics and viewer engagement patterns. The analysis combines two datasets containing title information and user engagement metrics to uncover relationships between variables such as genre, duration, release year, and popularity.

The goal is to transform raw data into meaningful insights using Python and data visualisation techniques.

---

## 🎯 Objectives  

- Analyse how viewer engagement varies across different Netflix titles  
- Explore relationships between content characteristics (genre, duration, release year) and popularity  
- Identify patterns in content growth and audience behaviour  
- Perform data cleaning, transformation, and feature engineering for analysis  

---

## 🛠️ Technologies Used  

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 📂 Project Structure  
# 🎬 Netflix Data Analysis using Python (Pandas)

## 📌 Project Overview  
This project performs an exploratory data analysis (EDA) on Netflix datasets to understand content characteristics and viewer engagement patterns. The analysis combines two datasets containing title information and user engagement metrics to uncover relationships between variables such as genre, duration, release year, and popularity.

The goal is to transform raw data into meaningful insights using Python and data visualisation techniques.

---

## 🎯 Objectives  

- Analyse how viewer engagement varies across different Netflix titles  
- Explore relationships between content characteristics (genre, duration, release year) and popularity  
- Identify patterns in content growth and audience behaviour  
- Perform data cleaning, transformation, and feature engineering for analysis  

---

## 🛠️ Technologies Used  

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 📂 Project Structure
notebooks/ → Jupyter Notebook containing full analysis
report/ → PDF version of the project report
data/ → Netflix datasets used in analysis
README.md → Project documentation

---

## 🔍 Data Description  

The project uses two datasets:

- **netflix_main.csv** → Contains metadata about Netflix titles (type, title, country, release year, duration, genre, etc.)  
- **netflix_ratings.csv** → Contains viewer engagement data (viewer rating and rating count)  

These datasets are merged using a common key (`show_id`) to create a complete dataset for analysis.

---

## ⚙️ Key Steps Performed  

### 1. Data Loading & Understanding  
- Loaded datasets directly from Google Drive using file IDs  
- Inspected structure, shape, and column information  

### 2. Data Cleaning & Preprocessing  
- Handled missing values using appropriate strategies  
- Removed unnecessary columns  
- Standardised text data  
- Converted data types (e.g., date columns)  

### 3. Feature Engineering  
- Created new variables such as:
  - `duration_numeric`  
  - `primary_genre`  
  - `added_year`  

### 4. Exploratory Data Analysis  
- Summary statistics for key variables  
- Distribution analysis using histograms and boxplots  
- Scatterplots to examine relationships  
- Genre-based comparisons  
- Time-based trends (content added per year)  
- Correlation heatmap  

---

## 📊 Key Insights  

- Viewer engagement varies significantly across titles but shows **weak correlation with duration and release year**  
- Certain genres demonstrate higher engagement compared to others  
- Netflix content growth shows a clear increasing trend over time  
- Viewer behaviour is influenced more by **content type and genre** than by duration or age of content  

---

## 🚀 Key Skills Demonstrated  

- Data cleaning and preprocessing using Pandas  
- Exploratory data analysis (EDA)  
- Data visualisation and storytelling  
- Feature engineering  
- Working with real-world datasets  
- Analytical thinking and interpretation  

---

## 📌 Conclusion  

This project demonstrates how raw data can be transformed into actionable insights through structured analysis and visualisation. It highlights the importance of data preprocessing, feature engineering, and exploratory analysis in understanding real-world datasets.

---

## 📎 Files  

- 📓 Notebook: Full analysis with code and visualisations  
- 📄 Report: Structured written explanation of the project  
- 📊 Data: Sample datasets used for analysis  

---

## 💡 Future Improvements  

- Apply machine learning models to predict viewer engagement  
- Perform clustering to group similar content  
- Include additional features such as cast, reviews, or sentiment analysis  
- Analyse time-based viewing behaviour  

