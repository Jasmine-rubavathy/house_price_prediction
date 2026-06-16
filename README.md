# 🏠 House Price Prediction (Google Colab Project)

## 📌 Objective

To predict house prices using machine learning regression models based on various input features.

---

## ☁️ Platform Used

This project was developed and executed using **Google Colab**, which allows running Python code in the cloud without local setup.

---

## 📊 Dataset

The dataset is taken from Kaggle and contains features like area, number of rooms, location, etc., used to predict house prices.

---

## 🛠️ Technologies Used

* Python 🐍
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn

---

## 🔍 Steps Performed

* Data Cleaning
* Handling Missing Values
* Feature Engineering
* Log Transformation
* Encoding & Scaling
* Model Training

---

## 🤖 Models Used

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor

---

## 📏 Evaluation Metrics

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)

---

## 🏆 Result

The best model was selected based on the lowest RMSE value.

---

## 📂 Files

* `house_price.ipynb` → Jupyter Notebook (downloaded from Colab)
* `house_model.pkl` → Saved trained model

---

## ▶️ How to Run (Using Google Colab)

1. Open Google Colab
2. Upload the notebook file (`task2_ML.ipynb`)
3. Upload dataset (if required)
4. Run all cells step by step
5. Model will be trained and saved

---

## 💾 How Model is Saved

```python
import pickle
pickle.dump(model, open("house_model.pkl", "wb"))
```

---

## 🔮 How to Use the Model

```python
import pickle

model = pickle.load(open("house_model.pkl", "rb"))
prediction = model.predict([[...input features...]])
print(prediction)
```



## ✅ Conclusion

This project shows how machine learning models can be built and deployed using Google Colab for real-world prediction tasks.

