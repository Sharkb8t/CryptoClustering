# 📖 Crypto Clustering - Unsupervised Machine Learning Project

## 📌 Project Overview

This project applies **unsupervised machine learning** techniques to analyze **cryptocurrency market data**. Using **K-Means clustering**, we group cryptocurrencies based on their **24-hour and 7-day price changes**. Additionally, we optimize the clustering process by reducing dimensionality with **Principal Component Analysis (PCA)**.

## 📁 Files in This Repository

📙 `Crypto_Clustering.ipynb` - The main Jupyter Notebook containing all the code and analysis.

📊 `crypto_market_data.csv` - The dataset used for clustering cryptocurrencies.

🗒️ `README.md` - This file, providing an overview of the project.

## 🛠 Technologies Used

🐍 Python

📙 Jupyter Notebook

🐼 Pandas

🤓 Scikit-learn (for K-Means & PCA)

📉 hvPlot (for interactive data visualization) 

## 📊 Steps Completed

### 1️⃣ Data Preprocessing

- Loaded the `crypto_market_data.csv` dataset.

- Standardized numerical features using **`StandardScaler()`**.

### 2️⃣ Finding the Best `k` (Elbow Method)

- Applied **K-Means clustering** to the **scaled dataset**.

- Used the **Elbow Method** to determine the optimal number of clusters.

### 3️⃣ Clustering Cryptocurrencies

- Applied **K-Means** with the best `k` value to group cryptocurrencies.

- Visualized the results using **hvPlot scatter plots**.

### 4️⃣ Dimensionality Reduction with PCA

- Reduced the dataset to **3 principal components**.

- Calculated the **total explained variance**.

### 5️⃣ Finding the Best `k` Using PCA Data

- Re-ran the **Elbow Method** on PCA-transformed data.

- Determined whether `k` changed after PCA optimization.

### 6️⃣ Clustering with PCA Data

- Applied **K-Means clustering** on the PCA-transformed data.

- Visualized the new clusters.

### 7️⃣ Comparing Results

- Compared **original clustering vs. PCA clustering**.

- Analyzed the impact of **reducing features with PCA**.

## 📌 Key Findings

- The **best `k` value** for clustering was found using the **Elbow Method** (4).

- PCA helped **reduce dimensionality** while retaining most of the data variance.

- The clustering results **changed slightly** after PCA.

## **📥 Installation & Setup**

1️⃣ Clone this repository:  
   ```bash
   git clone https://github.com/Sharkb8t/CryptoClustering.git
   ```

3️⃣ Install required libraries (if not already installed):
   ```bash
   pip install pandas scikit-learn hvplot
   ```

2️⃣ Open Jupyter Notebook `Crypto_Clustering` and run all cells sequentially.

