# NYC Taxi Trip Prediction
Author: Phuong Trang Tran
Student ID: 1409465

# NYC Taxi Trips, Fare, and Tips Prediction  

This project predicts the **number of taxi trips, fare amounts, and tips** in New York City while accounting for the effects of **weather conditions** and **seasonal holidays**.  

---

## Project Structure  

- **Notebooks**  
  - `Downloading_&_preprocess_1.ipynb` – Collects raw TLC data and cleans invalid fare values  
  - `Preprocess_weather_data.ipynb` – Preprocessing of weather datasets  
  - `Preprocess_2.ipynb` – Drops irrelevant features and fixes invalid entries  
  - `Data_analysis_notebook.ipynb` – Exploratory analysis of time, season, weather, and holidays  
  - `Predicting_MLmod.ipynb` – Model training and evaluation (Random Forest, Gradient Boosting)  

- **Directories**  
  - `data/` – Raw and processed datasets  
    - `processed_data/` – Cleaned taxi & weather datasets ready for modeling  
    - `training_testing_data/` – Train/test splits for ML models  
  - `plots/` – Visualizations from analysis  
  - `weather_data/` – Weather CSV files  

---

## Current Status  

- Data collection and preprocessing complete  
- Exploratory data analysis completed  
- Predictive models implemented  
- Results & insights obtained  

---

## Requirements  

- Python 3.10.18  
- PySpark  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Gradient Boosting libraries  

Install dependencies with:  

```bash
pip install -r requirements.txt
