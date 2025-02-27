# Rental Price Prediction

## Project Overview
This project aims to predict rental prices in a city based on various independent features such as location, area, number of bedrooms, and amenities. Using machine learning techniques, we developed models to help individuals estimate rental costs accurately, assisting them in making informed housing decisions.

## Motivation
In recent years, it has become increasingly common for individuals to move to bigger cities in search of job opportunities. The first thing they look for is not buying a house but renting one. Rental markets are significantly larger compared to home-buying markets, especially in cities like Hyderabad, which are emerging as IT hubs in a rapidly developing country like ours. This project aims to simplify rental price estimation for individuals looking for housing.

## Dataset Details
- The dataset contains various independent features related to rental properties.
- Features include **location, area, number of bedrooms, number of bathrooms, availability of amenities**, etc.
- Data preprocessing steps included handling missing values, encoding categorical features, and feature scaling.
- The original dataset can be found [here](Original_Hyderabad_House_Data.csv).

## Machine Learning Models Used
We implemented and compared the following models:

### **1️. Random Forest Regressor**
**Training Performance:**
- Root Mean Squared Error: **0.1407**
- Mean Absolute Error: **0.0947**
- R2 Score: **0.9204**

**Test Performance:**
- Root Mean Squared Error: **0.1756**
- Mean Absolute Error: **0.1211**
- R2 Score: **0.8703**

---

### **2️. XGBoost Regressor**
**Training Performance:**
- Root Mean Squared Error: **0.1557**
- Mean Absolute Error: **0.1123**
- R2 Score: **0.9025**

**Test Performance:**
- Root Mean Squared Error: **0.1749**
- Mean Absolute Error: **0.1274**
- R2 Score: **0.8713**

## Installation & How to Run
### **1️. Clone the Repository**
```bash
git clone https://github.com/SAI-KRISHNA07/Rental-Price-Prediction.git
cd Rental-Price-Prediction
```

### **2️. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️. Run the Jupyter Notebook**
```bash
jupyter notebook
```
Open `rental_price_prediction.ipynb` and execute the cells to train and evaluate the models.

## Future Improvements
- Incorporate **more features** such as crime rate, distance from IT hubs, and transportation facilities.
- Optimize hyperparameters further for improved model accuracy.
- Deploy the model using **Streamlit** or **Flask** for real-time rental price predictions.
- Explore **deep learning approaches** for better generalization.

## Contact
For any queries or collaborations, feel free to reach out via **GitHub Issues** or connect with me on **[LinkedIn](https://www.linkedin.com/in/sai-krishna-beeraka-bab540275/)**.

