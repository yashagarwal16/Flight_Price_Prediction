# ✈️ Flight Price Prediction

This project uses machine learning techniques to predict flight ticket prices based on various features such as departure time, arrival time, airline, source, destination, and other travel-related details.

---

## 📊 Dataset

The dataset used includes details like:
- Airline
- Date of Journey
- Source and Destination
- Route
- Duration
- Total Stops
- Price

## 🔧 Technologies Used

- Python 🐍
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- XGBoost *(if used)*

---

## ⚙️ How to Run

1. **Clone the repository** or download the notebook.

2. **Install required packages**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
````

3. **Launch the notebook using Jupyter**:

   ```bash
   jupyter notebook FlightPrediction.ipynb
   ```

---

## 🧪 Model Pipeline Overview

The notebook performs the following steps:

* Data preprocessing:

  * Handling missing values
  * Cleaning columns (e.g., converting duration and date formats)
* Feature engineering:

  * Extracting day, month, hour, etc.
  * Encoding categorical variables (One-Hot and Label Encoding)
* Model building:

  * Linear Regression
  * Random Forest Regressor
  * XGBoost Regressor *(if applicable)*
* Model evaluation:

  * R² Score
  * MAE (Mean Absolute Error)
  * MSE (Mean Squared Error)
* Hyperparameter tuning *(if done)*

---

## 📌 Key Features

* Handles missing and inconsistent data
* Converts categorical features into numeric form
* Supports model comparison and evaluation
* Can be extended to deploy on a web interface using Flask/Streamlit

---

## 📈 Future Improvements

* Integrate Flask or Streamlit for deployment
* Include cross-validation and hyperparameter tuning
* Use additional models like CatBoost or LightGBM
* Improve feature importance visualization

---

## 📄 License

This project is intended for educational and research purposes only. Please refer to the data source’s license for data usage rights.

---

## 👨‍💻 Author

* *Yash Agarwal*
* *https://github.com/yashagarwal16/Flight_Price_Prediction*

```

---

Let me know if you’d like me to:

- Generate this as a downloadable `README.md` file
- Insert specific dataset links or author details
- Help you deploy the model on a web interface (Flask/Streamlit)

Would you like the `.md` file now?
```
