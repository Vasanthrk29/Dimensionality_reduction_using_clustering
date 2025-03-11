# 🚀 Human Activity Recognition using Machine Learning

## 📌 Project Overview
This project focuses on **Human Activity Recognition (HAR)** using machine learning techniques. The dataset consists of **sensor data from smartphones**, and we aim to classify different human activities based on this data. 

We compare two models:
1. **Baseline Model (All Features)** using **Naïve Bayes**
2. **Feature Selection using K-Means Clustering** to reduce dimensionality before training

## 📂 Dataset Information
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones)
- The dataset contains **561 features** extracted from **accelerometer and gyroscope** readings of smartphones.
- Activities include **walking, standing, sitting, lying down, walking upstairs, and walking downstairs**.

## 🛠️ Data Preprocessing
✔️ Downloaded dataset automatically using web scraping
✔️ Handled missing values and encoded class labels
✔️ Standardized features for optimal performance
✔️ Applied **K-Means Clustering** for feature selection

## 🤖 Machine Learning Models Used
### **Baseline Model (All Features)**
- **Algorithm**: Naïve Bayes
- **Accuracy**: **73.15%**
- **Training Time**: **0.077 sec**
- **Number of Features**: **561**

### **Model with Feature Selection (K-Means)**
- **Algorithm**: Naïve Bayes
- **Feature Selection**: K-Means clustering (reduced features to 50)
- **Accuracy**: **82.93%** 🎯 (Higher than the baseline!)
- **Training Time**: **0.010 sec**
- **Number of Features**: **50** (Reduced from 561!)

## 📌 How to Run the Project
1. **Clone the repository**
   ```bash
   git clone https://github.com/Vasanthrk29/Dimensionality_reduction_using_clustering.git
   cd Dimensionality_reduction_using_clustering
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Python script**
   ```bash
   python Dimensionality_reduction_using_clustering.py
   ```

## 🚀 Future Enhancements
🔹 Experiment with **Deep Learning (LSTMs, CNNs)** for better accuracy
🔹 Use **t-SNE or PCA** for alternative feature selection
🔹 Deploy the model with **Flask or Streamlit** for real-time predictions

## 🏆 Contributors
👨‍💻 **Your Name** – [GitHub Profile](https://github.com/Vasanthrk29)

## 📜 License
This project is licensed under the **MIT License**. Feel free to use and modify!
