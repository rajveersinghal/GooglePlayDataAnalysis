# EDA and Feature Engineering of Google Play Store Dataset  

## Problem Statement  
Today, there are approximately 2.56 million apps available for download on the Google Play Store. These apps have significantly impacted our daily lives.  
The objective of this project is to analyze the dataset and answer key questions, such as:  
1. Which is the most popular category?  
2. Which app has the largest number of installs?  
3. What are the most installed apps in specific categories?  
4. Which apps have a perfect rating of 5?  

---

## Dataset Information  
- **Source**: [Google Play Store Dataset](https://raw.githubusercontent.com/krishnaik06/playstore-Dataset/main/googleplaystore.csv)  
- The dataset contains the following features:  
  - `App`, `Category`, `Rating`, `Reviews`, `Size`, `Installs`, `Type`, `Price`, `Content Rating`, and more.  
- **Shape**: The dataset contains **10,841 rows** and **13 columns**.  

---

## Steps Performed  

### 1. Data Cleaning  
- Removed duplicate rows and missing values.  
- Handled non-numeric values in columns like `Reviews`, `Size`, `Installs`, and `Price`.  
- Converted the `Last Updated` feature into separate `Day`, `Month`, and `Year` columns.  

### 2. Feature Engineering  
- Processed and cleaned features for better usability.  
- Extracted new columns such as `Year` and transformed size into a numeric format.  

### 3. Exploratory Data Analysis (EDA)  
- Analyzed the distribution of numerical features like `Reviews`, `Size`, `Installs`, and `Price`.  
- Explored the proportion of data in categorical columns like `Category`, `Type`, and `Content Rating`.  
- Visualized the most popular app categories and apps with the largest number of installs.  

---

## Key Insights  

1. **Popular App Categories**:  
   - Categories like `Family`, `Game`, and `Tools` dominate the Play Store.  
   - Categories such as `Beauty`, `Comics`, and `Weather` have fewer apps.  

2. **Top Installed Categories**:  
   - The category with the highest number of installations is `GAME`.  

3. **Most Installed Apps by Popular Categories**:  
   - Visualized the top 5 apps in categories like `GAME`, `COMMUNICATION`, `PRODUCTIVITY`, and `SOCIAL`.  

4. **Apps with 5-Star Ratings**:  
   - There are several apps with a perfect rating of 5, showcasing user satisfaction in certain niches.  

---

## Visualizations  

### 1. Distribution of Numerical Features  


### 2. Popular Categories by Installations  


### 3. Top 5 Apps in Popular Categories  


---

## Tools & Libraries Used  

- **Python**: Core programming language used.  
- **Libraries**:  
  - `pandas` for data manipulation.  
  - `numpy` for numerical operations.  
  - `matplotlib` and `seaborn` for visualizations.  
  - `warnings` to suppress warnings.  

---

## How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
