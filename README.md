**❤️ Heart Disease Prediction using Logistic Regression**

This project uses a machine learning model to predict whether a person has heart disease based on their medical attributes. It is built using Python and scikit-learn, and uses logistic regression for classification.

---

**📁 Dataset**

The dataset used in this project is `heart_disease_data.csv`, which contains various medical parameters of patients, along with a target column that indicates the presence (1) or absence (0) of heart disease.

**🧬 Features in the dataset may include:**

* 👴 Age
* 🚻 Sex
* 💢 Chest Pain Type (cp)
* 💓 Resting Blood Pressure (trestbps)
* 🩸 Serum Cholesterol (chol)
* 🍬 Fasting Blood Sugar (fbs)
* 📈 Resting ECG Results (restecg)
* 🏃‍♂️ Maximum Heart Rate (thalach)
* 😮‍💨 Exercise Induced Angina (exang)
* 📉 ST Depression (oldpeak)
* ⛰️ Slope of ST Segment (slope)
* 🫀 Major Vessels (ca)
* 🧪 Thalassemia (thal)

Note: These are typical columns in heart disease datasets like the UCI Heart Disease dataset.

---

**🎯 Objective**

To build a logistic regression model that can:

* 🔍 Predict the risk of heart disease
* ✅ Achieve high accuracy on training and test data
* 🤖 Predict disease status for new input data

---

**🔧 How it works**

1. **Data Preprocessing**

   * Load data using pandas
   * Check for null values
   * Split features and labels

2. **Model Training**

   * Train with Logistic Regression
   * Split into train and test sets

3. **Prediction**

   * Accept user input
   * Predict whether heart disease is present

---

**📊 Evaluation**

The model is evaluated using accuracy score.
Training and test performance are printed on screen.

---

**💻 Example Prediction Code**

```python
input_data = (57,1,0,140,192,0,1,148,0,0.4,1,0,1)
prediction = model.predict(np.asarray(input_data).reshape(1, -1))

if prediction[0] == 0:
    print("The person does NOT have heart disease.")
else:
    print("The person HAS heart disease.")
```

---

**🛠️ Libraries Used**

* numpy
* pandas
* scikit-learn

---

**🚀 How to Run**

1. Clone the repository:
   cd heart-disease-prediction

2. Install required libraries:
   pip install -r requirements.txt

3. Run the notebook:
   jupyter notebook heart\_disease.ipynb


Let me know if you want this exported as a file (`README.md`) or need help adding it directly to your GitHub repository.
