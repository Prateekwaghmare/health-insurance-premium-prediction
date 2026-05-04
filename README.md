# 🏥 Health Insurance Premium Prediction

A Machine Learning web application built using Streamlit that predicts health insurance premiums based on user details such as age, income, medical history, lifestyle, and more.

---

## 🚀 Features

* Predicts insurance premium instantly
* User-friendly web interface using Streamlit
* Handles categorical and numerical data
* Uses trained ML models for different age groups
* Includes preprocessing and feature engineering

---

## 🧠 Machine Learning Models

The project uses two separate models:

* **Young Model** → For users age ≤ 25
* **Rest Model** → For users age > 25

Both models are trained and saved using `joblib`.

---

## 📂 Project Structure

```
health-insurance-premium-prediction/
│
├── artifacts/
│   ├── model_young.joblib
│   ├── model_rest.joblib
│   ├── scaler_young.joblib
│   ├── scaler_rest.joblib
│
├── main.py
├── prediction_helper.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/health-insurance-premium-prediction.git
cd health-insurance-premium-prediction
```

2. Create a virtual environment:

```bash
python -m venv venv
```

3. Activate environment:

* Windows:

```bash
venv\Scripts\activate
```

* Linux/Mac:

```bash
source venv/bin/activate
```

4. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run main.py
```

---

## 📊 Input Features

The model uses the following inputs:

* Age
* Gender
* Number of Dependants
* Income (in Lakhs)
* Insurance Plan (Bronze/Silver/Gold)
* Medical History
* BMI Category
* Smoking Status
* Employment Status
* Region
* Marital Status
* Genetical Risk

---

## 🔍 How It Works

1. User inputs data via Streamlit UI
2. Data is preprocessed and encoded
3. Risk score is calculated based on medical history
4. Appropriate scaler and model are selected
5. Model predicts insurance premium

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Pandas
* Scikit-learn
* Joblib

---

## ⚠️ Important Notes

* Ensure all `.joblib` files are present in the `artifacts/` folder
* Remove incorrect imports like:

```python
from cffi import model
```

* Make sure all dependencies are listed in `requirements.txt`

---

## 🌐 Deployment

You can deploy this app on:

* Streamlit Cloud
* Render
* Heroku

---

## 📌 Future Improvements

* Add more accurate models
* Improve UI design
* Add data visualization
* Enable API integration

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author


💻 GitHub: Prateek Waghmare
🔗 LinkedIn: Prateek Waghmare

---
## 🌐 Live Demo

🚀 Experience the app in real-time:

🔗 **[Launch App](https://prateek-health-insurance-premium-prediction.streamlit.app/)**

> Predict health insurance premiums instantly using ML 🚑📊
---
## 📸 App Screenshots

<p align="center">
  <img src="assets/screenshot1.png" width="45%" />
  <img src="assets/screenshot2.png" width="45%" />
</p>
