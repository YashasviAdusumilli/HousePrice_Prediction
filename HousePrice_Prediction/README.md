🏠 House Price Prediction - Data Science Project

📌 Overview
This project uses Linear Regression to predict house prices based on features like square footage, number of bedrooms, bathrooms, and location (zipcode). The dataset contains 21,000+ house sale records from King County, USA.

## 📂 Dataset
- Source: [Kaggle: House Sales in King County, USA](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)
- Features used:
  - sqft_living, bedrooms, bathrooms, floors, zipcode
- Target: `price`

## 🧼 Data Preprocessing
- Selected relevant features
- Handled categorical variable `zipcode` using one-hot encoding
- No missing values

## 🤖 Model Used
- **Linear Regression** from Scikit-learn
- Trained on 80% of data, tested on 20%

## 📊 Evaluation Metrics
- **Mean Squared Error (MSE):** _<insert_value>_
- **R² Score:** _<insert_value>_
- The model performs well on mid-range houses but has higher error for luxury properties

## 📈 Visualization
![Actual vs Predicted](model_visuals.png)

## 📚 Learnings
- Data preprocessing is key
- Simple models can perform well with proper feature selection
- Model struggled with expensive homes → could improve with more features or advanced models

## 💡 Future Improvements
- Try Random Forest, XGBoost
- Use features like `grade`, `condition`, `renovation`, `view`, `waterfront`
- Hyperparameter tuning

## 🚀 Try It Yourself
Run the full project in [Google Colab](https://colab.research.google.com/)  
Use: `house_price_model.ipynb`

---

Made by Yashasvi Adusumilli.
