🏠 House Price Prediction using Decision Tree Regressor

 Overview:

This project demonstrates a simple **House Price Prediction** model using **Decision Tree Regression** in Python. The model predicts house prices based on three features:

* Square Feet (SqFt)
* Number of Bedrooms
* Age of the House

The project also evaluates the model using **Mean Absolute Error (MAE)** and **R² Score**, and visualizes the predicted prices against the actual prices.

---

 Features:

* Create a sample housing dataset using Pandas.
* Split data into training and testing sets.
* Train a Decision Tree Regressor.
* Predict house prices.
* Evaluate model performance using:

  * Mean Absolute Error (MAE)
  * R² Score
* Visualize Actual vs Predicted Prices using Matplotlib.

---

Technologies Used:

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

 Installation:

Clone the repository:

```bash
git clone https://github.com/yourusername/House-Price-Prediction.git
```

Move into the project directory:

```bash
cd House-Price-Prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

 Dataset:

The project uses a small sample dataset created directly inside the Python program.

| SqFt | Bedrooms | Age |  Price |
| ---: | -------: | --: | -----: |
| 1200 |        2 |  15 | 180000 |
| 1500 |        3 |  10 | 220000 |
| 1800 |        3 |   5 | 260000 |
| 2400 |        4 |   2 | 350000 |
| 3000 |        4 |   1 | 450000 |
| 1100 |        2 |  20 | 165000 |
| 1400 |        3 |  12 | 210000 |
| 2200 |        3 |   8 | 310000 |
| 2800 |        4 |   4 | 410000 |
| 3500 |        5 |   1 | 520000 |

---

 Model:

The project uses:

```python
DecisionTreeRegressor(max_depth=3, random_state=42)
```

The model is trained using:

* 80% Training Data
* 20% Testing Data

---

 Evaluation Metrics:

The following metrics are used:

* Mean Absolute Error (MAE)
* R² Score

---

 Visualization:

A scatter plot compares the **Actual House Prices** with the **Predicted House Prices**.

* Blue dots represent predictions.
* Red diagonal line represents perfect predictions.

---

 Example Output:

```text
Mean Absolute Error: $35000

R² Score: 0.91

Predicted Prices:
[310000. 450000.]
```

*(Values may vary depending on the train-test split.)*

---

 Future Improvements:

* Use a larger real-world housing dataset.
* Perform feature engineering.
* Tune hyperparameters using GridSearchCV.
* Compare Decision Tree with Random Forest and Gradient Boosting.
* Save the trained model using Joblib or Pickle.
* Build a web application using Flask or Streamlit.

---

 Author:

Developed as a beginner machine learning project using Python and Scikit-learn.
