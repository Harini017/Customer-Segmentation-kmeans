
![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-brightgreen?logo=streamlit)
![GitHub](https://img.shields.io/badge/Code-GitHub-blue?logo=github)

# 🧠 Customer Segmentation using KMeans Clustering

This project uses **KMeans Clustering** to segment mall customers based on demographic and behavioral data. It helps businesses better understand their customer base and personalize marketing strategies.

---

## 🔗 Live Demo

👉 [View App on Streamlit](https://harini017-customer-segmentation-kmeans-app-cpz2vo.streamlit.app)

---

## 📊 Features

* Upload and explore customer dataset
* Perform **KMeans clustering** interactively
* Visualize clusters using **Seaborn** & **Matplotlib**
* Choose custom number of clusters (`k`)
* Download clustered output as CSV

---

## 📁 Dataset

* **File:** `Synthetic_Mall_Customers_500.csv`
* **Columns:**

  * `Customer ID`, `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1–100)`

---

## ⚙️ Tech Stack

* **Python 3**
* **Libraries:**
  `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`
* **Web App:** [Streamlit](https://streamlit.io/)

---

## 🚀 Run Locally

```bash
git clone https://github.com/Harini017/Customer-Segmentation-kmeans.git
cd Customer-Segmentation-kmeans
pip install -r requirements.txt
streamlit run app.py
```

---

## 📁 Project Structure

```
Customer-Segmentation-kmeans/
├── app.py                          # Streamlit app
├── requirements.txt               # Python dependencies
├── Synthetic_Mall_Customers_500.csv  # Dataset
└── README.md                      # Project info
```


