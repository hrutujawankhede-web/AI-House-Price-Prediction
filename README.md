# 🏠 AI-Powered House Price Prediction System

An AI-powered web application built using **Machine Learning** and **Streamlit** to predict house prices based on property features. The application provides interactive visualizations, AI-generated insights, and a user-friendly dashboard for estimating property values.

---

## 📌 Project Overview

This project predicts the estimated price of a house using a **Random Forest Regression** model trained on housing data.

Users can enter details such as:
- Area
- Number of Bedrooms
- Number of Bathrooms
- Number of Stories
- Parking Spaces

The application instantly predicts the house price and provides useful market insights.

---

## ✨ Features

- 🏠 House Price Prediction
- 🤖 AI-based Property Insights
- 📊 Interactive Market Analysis
- 📈 Price Distribution Visualization
- 📉 Area vs Price Analysis
- 📋 Property Information Dashboard
- 🎨 Modern Streamlit User Interface

---

## 🧠 Machine Learning Model

**Algorithm Used**

- Random Forest Regressor

### Why Random Forest?

- High prediction accuracy
- Handles non-linear relationships
- Less prone to overfitting
- Suitable for regression problems

---

## 📂 Dataset

**Dataset Name:**

Housing Prices Dataset

Dataset contains:

- 545 House Records
- 13 Features

### Features

| Feature | Description |
|----------|-------------|
| price | Target Variable |
| area | Area of House |
| bedrooms | Number of Bedrooms |
| bathrooms | Number of Bathrooms |
| stories | Number of Floors |
| mainroad | Main Road Access |
| guestroom | Guest Room |
| basement | Basement |
| hotwaterheating | Hot Water Heating |
| airconditioning | Air Conditioning |
| parking | Parking Spaces |
| prefarea | Preferred Area |
| furnishingstatus | Furnishing Status |

---

## ⚙️ Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Plotly
- Joblib

---

## 📁 Project Structure

```
House-price-ai-project/
│
├── app.py
├── train.py
├── requirements.txt
│
├── datasets/
│   └── House price ai.csv
│
├── models/
│   └── model.pkl
│
└── README.md
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/House-price-ai-project.git
```

Move into the project folder

```bash
cd House-price-ai-project
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

## 📊 Application Workflow

1. Load the housing dataset
2. Preprocess categorical features
3. Train the Random Forest model
4. Save the trained model
5. User enters house details
6. Model predicts the price
7. Display AI insights and charts

---

## 📈 Future Enhancements

- Location-wise Price Prediction
- Similar Property Recommendation
- PDF Report Generation
- Interactive Maps
- Property Investment Score
- AI Chat Assistant
- Real-time Property Listings

---

## 👩‍💻 Author

**Hrutuja Wankhede**

B.Tech – Computer Science and Business Systems (CSBS)

AI & Machine Learning Enthusiast

---

## 📜 License

This project is licensed under the MIT License.
