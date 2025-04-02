# **Air Quality Prediction using Machine Learning**  

## **📌 Project Overview**  
This project analyzes air quality data by performing **data preprocessing, exploratory data analysis (EDA), and machine learning modeling**. Various regression and classification models were implemented to predict **AQI (Air Quality Index)** based on pollutant levels.  

## **📂 Dataset Description**  
The dataset contains air pollution data with the following key columns:  
- **state & location:** Region where the air quality was measured.  
- **so2, no2, rspm, spm, pm2_5:** Different air pollutants affecting AQI.  
- **SI, NI, RPI, SPI, AQI:** Calculated indices for air pollution impact.  
- **sampling_date:** Date of sample collection (used in time series analysis).  

## **🛠 Technologies Used**  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Visualization Tools:** Power BI  

## **🔎 Exploratory Data Analysis (EDA)**  
- Handled missing values using **mean, median, mode, fillna, and dropna**.  
- Performed **summary statistics, correlation analysis, and data visualization**.  
- Created **heatmaps, boxplots, and scatter plots** to understand pollutant trends.  

## **📊 Machine Learning Models**  

### **1️⃣ Regression Models**  
- **Linear Regression (LR)** → RMSE: 46.52 | R²: 0.85  
- **Decision Tree (DT)** → RMSE: 1.09 | R²: 0.99  
- **Random Forest (RF)** → RMSE: **1.02** | R²: **0.99** ✅ (Best)  

### **2️⃣ Classification Models**  
- **Logistic Regression** → Accuracy: 39.1% | Kappa Score: 0.20  
- **Decision Tree (DT)** → Accuracy: **99.99%** | Kappa Score: 0.99 ✅ (Best)  
- **Random Forest (RF)** → Accuracy: **99.98%** | Kappa Score: **0.99** ✅  
- **KNN** → Accuracy: **99.14%** | Kappa Score: **0.98**  

## **🏆 Conclusion**  
- **Random Forest (RF) performed the best in both regression & classification.**  
- Time series analysis (ARIMA, SARIMA) can be explored for future AQI forecasting.  
- Power BI was used to create **interactive dashboards** for better insights.  

## **📎 Project Structure**  
```plaintext
Air-Quality-Data-India-Analysis/
│-- 1. 📘 Air Quality Data India Analysis.ipynb   # Jupyter Notebook with analysis & modeling
│-- 2. 📊 Dashboard on cleaned csv/               # Folder containing Power BI dashboards & screenshots
│-- 3. 🖥️ PPT.pptx                                # Presentation explaining approach, insights & findings
│-- 4. 📝 cleaned_data.xlsx                        # Processed & cleaned dataset
│-- 5. 📄 data.xlsx                                # Raw dataset
│-- 6. 📜 README.md                                # Project documentation & setup instructions 
