
# 🏡 House Price Prediction

This project is a **Machine Learning model** that predicts house prices based on various input features such as location, size, number of bedrooms, bathrooms, and more. It uses a Linear Regression model trained on the popular **Bengaluru House Price dataset**.

---

## 📁 Project Structure

- `House_Price_Prediction.ipynb`: Main Jupyter Notebook containing data preprocessing, visualization, model building, and evaluation.
- `README.md`: Project documentation and overview (you are reading it!).

---

## 📊 Dataset

- **Source**: [Kaggle - Bengaluru House Price Data](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)
- **Features Used**:
  - Location
  - Size (BHK)
  - Total square feet
  - Number of bathrooms
  - Price

---

## 📌 Problem Statement

To predict house prices using features from the dataset and to deploy a model that generalizes well on unseen data. The major steps involve:
- Data cleaning
- Feature engineering
- Outlier removal
- Model training (Linear Regression)
- Evaluation

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for data visualization
- **Scikit-learn** for machine learning model building

---

## 🔍 Key Steps

1. **Data Preprocessing**
   - Handled missing values
   - Extracted BHK info
   - Converted total_sqft to numeric
   - Removed outliers

2. **Feature Engineering**
   - Used one-hot encoding for locations
   - Created a cleaned and usable dataset

3. **Model Building**
   - Used Linear Regression
   - Applied `GridSearchCV` for hyperparameter tuning

4. **Evaluation**
   - Split data using `train_test_split`
   - Achieved good performance on test data

---

## 📈 Output Example

```python
Enter location: Rajaji Nagar
Enter square feet: 1500
Enter number of bathrooms: 3
Enter BHK: 3
Predicted Price: ₹145.6 Lakhs
````

---

## 🚀 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/BhardwajChakri7/house-price-prediction.git
   cd house-price-prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook House_Price_Prediction.ipynb
   ```

---

## ✅ Future Improvements

* Model deployment with Flask/Django
* Use of more advanced algorithms like XGBoost or Random Forest
* Frontend interface for user input and result visualization

---

## 📬 Contact

Created by **Ganipineni Bhardwaj Naidu**
Feel free to reach out for feedback or collaboration opportunities!

```

---

Let me know if you'd like:
- A downloadable `.md` file of this README.
- A `requirements.txt` generated from the notebook.
- Help renaming the notebook file itself.
```
