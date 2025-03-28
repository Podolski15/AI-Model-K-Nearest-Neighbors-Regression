

# **Price Prediction Using K-Nearest Neighbors (KNN)**  

## 📌 **Project Overview**  
This project focuses on developing an AI model using **K-Nearest Neighbors (KNN) regression** to predict the price of **Airbnb listings in Boston**. The project follows a structured AI learning pipeline:  

✔ **Data Preprocessing** – Cleaning and transforming data  
✔ **Exploratory Data Analysis (EDA)** – Understanding trends and relationships  
✔ **Feature Engineering** – Selecting the most relevant features  
✔ **Model Training & Evaluation** – Testing different **K values** to optimize performance  

The dataset used is the **Airbnb Boston dataset** from **Kaggle**, and this project demonstrates the practical application of **KNN for regression problems** in price prediction.  

---

## 🔍 **Key Findings**  

- **Best K Value**: The optimal `k` found was **19**, which provided the best model performance.  
- **Pricing Trends**:  
  - Listings with **more bedrooms & bathrooms** tend to be priced higher.  
  - **Entire homes/apartments** are generally more expensive than private/shared rooms.  
  - Listings that **accommodate more guests** have higher prices (except luxury properties).  
  - **Review scores have a minor impact** on price.  
  - **Availability affects pricing**—properties available for more days tend to have more competitive pricing.  
- **Model Effectiveness**: The KNN model explains **66.27%** of the variance in prices, meaning external factors not included in the dataset also influence Airbnb pricing.  

---

## 📂 **Dataset**  
**Source**: [Airbnb Boston Open Dataset (Kaggle)](https://www.kaggle.com)  

**Key Features Used:**  
✔ `property_type`  
✔ `room_type`  
✔ `accommodates`  
✔ `bathrooms`, `bedrooms`, `beds`  
✔ `review_scores_rating`  
✔ `availability_365`  

**Preprocessing Steps:**  
- Handling **missing values**  
- Encoding **categorical variables**  
- Standardizing **numerical features**  

---

## 🛠 **Model Selection: K-Nearest Neighbors Regression**  

📌 **Best K Value**: 🔢 `19`  
📌 **Mean Absolute Error (MAE)**: 📉 `0.2813`  
📌 **Mean Squared Error (MSE)**: 📉 `0.1276`  
📌 **Root Mean Squared Error (RMSE)**: 📉 `0.3573`  
📌 **R² Score**: 🎯 `0.6627`  

**Strongest Predictors of Price:**  
🏡 **Property Type** – Luxury listings have higher prices  
🛏 **Room Type** – Entire homes/apartments are the most expensive  
📊 **Bedrooms & Accommodates** – More bedrooms & guest capacity generally lead to higher prices  

---

## 🚀 **Future Improvements**  

✔ **Explore More Complex Models** – Decision Trees or Gradient Boosting models might improve accuracy.  
✔ **Enhance Feature Selection** – Adding **price per bedroom** or **host experience level** could help.  
✔ **Optimize Computational Efficiency** – KNN is not the most efficient for large datasets.  

