# 🚗 Car Price Prediction using Linear Regression

Welcome to **Car Price Predictor** — a simple yet powerful machine learning project that predicts the price of a car using **Linear Regression**! Whether you're a data science enthusiast or a car lover, this project transforms raw vehicle data into meaningful price insights.
## 🎯 Project Goal
Estimate car prices based on key vehicle attributes. This project highlights:

- 📊 Linear Regression model building  
- 🧹 Data cleaning & preprocessing  
- 🚘 Predicting prices of unseen vehicles
  ## ⚙️ Tech Stack

- Python  
- Scikit-learn (`LinearRegression`)  
- Pandas & NumPy  
- Matplotlib & Seaborn (Visualizations)  
- Jupyter Notebook  
## 🔑 Features Used

| Feature         | Description                         |
|----------------|-------------------------------------|
| `name`         | Car name/brand (encoded)            |
| `year`         | Year of manufacture                 |
| `km_driven`    | Kilometers driven                   |
| `fuel`         | Fuel type (encoded)                 |
| `seller_type`  | Dealer/Individual (encoded)         |
| `transmission` | Manual/Automatic (encoded)          |
| `owner`        | Number of previous owners           |
| `mileage`      | Mileage (km/l or km/kg)             |
| `engine`       | Engine size (CC)                    |
| `max_power`    | Maximum power (bhp)                 |
| `seats`        | Number of seats                     |



```markdown
## 🧪 Example Prediction

```python
import pandas as pd

# Sample input
input_data_model = pd.DataFrame(
    [[4, 2024, 30000, 2, 1, 1, 1, 21.1, 814, 52.8, 9.0]],
    columns=[
        'name', 'year', 'km_driven', 'fuel', 'seller_type',
        'transmission', 'owner', 'mileage', 'engine', 'max_power', 'seats'
    ]
)

predicted_price = model.predict(input_data_model)
print(f"Predicted Price: {predicted_price[0]:,.2f}")
📉 Sample Output
Predicted Price: 496,290.89 

# Car Price Prediction Web App  
An interactive Streamlit application that predicts used car prices based on various features using a Linear Regression model.

---

## Features  
- Predict car prices instantly based on inputs like brand, year, fuel type, mileage, and more.  
- Easy-to-use Streamlit interface for smooth user experience.  
- Built with Python, Scikit-learn, and deployed on Streamlit Cloud.

---

## Demo  
Try the live demo here:  

👉 [Open the Car Price Prediction Web App](https://car-price-prediction-kfa7dwa78ythfejgtrlrpp.streamlit.app/)

---

## Installation  
Clone the repository:  
```bash
git clone https://github.com/juhi-shahi/car-price-prediction.git
cd car-price-prediction








