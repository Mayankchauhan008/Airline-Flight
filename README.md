# Airlines Flights Data Analysis ✈️

This project performs an end-to-end analysis of airline flight data to explore trends, visualize patterns, and build predictive models.  
The goal is to compare different regression algorithms for predicting flight-related metrics.

---

## 📂 Dataset
**File:** `airlines_flights_data.csv`  
The dataset contains details of airline flights, including various features like departure time, arrival time, delays, and more.  

**Preprocessing steps:**
- Dropped irrelevant columns (e.g., `index`)
- Removed missing values
- Prepared numerical and categorical features for modeling

---

## 📊 Data Analysis & Visualization
Using **pandas**, **matplotlib**, and **seaborn**, the following analyses were conducted:
- Distribution of flight delays
- Relationships between numerical features
- Correlation heatmaps
- Outlier detection and handling

---

## 🤖 Machine Learning Models
The following **five** regression models were trained and compared:
1. **Linear Regression**
2. **Decision Tree Regression**
3. **Random Forest Regression**
4. **CatBoost Regression**
5. **XGBoost Regression**

**Workflow:**
1. **Data Splitting** — Train-test split
2. **Model Training** — Fit models to training data
3. **Model Evaluation** — Compare using metrics like:
   - Mean Squared Error (MSE)
   - R² Score
4. **Visualization** — Plot actual vs. predicted values

---

## ⚙️ Installation
```bash
pip install pandas numpy scikit-learn matplotlib seaborn catboost xgboost

```
📌 Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- catboost
- xgboost

📜 License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/Mayankchauhan008/Airline-Flight/blob/main/LICENSE) file for details.
