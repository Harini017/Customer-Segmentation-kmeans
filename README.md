# 🧠 Customer Segmentation using KMeans Clustering

This project uses KMeans Clustering to segment mall customers based on demographic and behavioral data. The goal is to help businesses understand their customer base and personalize marketing strategies.

## 🔗 Live Demo

👉 (https://harini017-customer-segmentation-kmeans-app-cpz2vo.streamlit.app


## 📊 Features

- Upload and explore customer dataset
- Perform KMeans clustering interactively
- Visualize clusters with Seaborn & Matplotlib
- Customize number of clusters (`k`)
- Download the clustered output


## 📁 Dataset

- **Name:** Synthetic_Mall_Customers_500.csv  
- **Fields:**  
  - `Customer ID`, `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1–100)`


## ⚙️ Tech Stack

- **Python 3**
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`
- **Web App:** [Streamlit](https://streamlit.io/)



## 🚀 Run Locally

```bash
git clone https://github.com/Harini017/Customer-Segmentation-kmeans.git
cd Customer-Segmentation-kmeans
pip install -r requirements.txt
streamlit run app.py




---------------------------------

## 📁 Project Structure

Customer-Segmentation-kmeans/
│
├── app.py                    # Streamlit app source
├── requirements.txt          # Python dependencies
├── Synthetic_Mall_Customers_500.csv  # Dataset
└── README.md                 # You're here!

