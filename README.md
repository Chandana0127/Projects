# Projects
This repository contains various projects related to data science and machine learning. Below is an overview of the current project in this repository.

# DYNAMIC ENSEMBLE TECHNIQUE FOR DNA ENHANCER PREDICTION USING MACHINE LEARNING METHODS

# 📌 Project Overview  
DNA enhancers are crucial **non-coding sequences** that regulate gene expression, impacting various biological processes and disease mechanisms. This project implements a **dynamic ensemble learning approach** that combines multiple machine learning and deep learning models to **accurately predict DNA enhancer sequences**.  

## 🚀 Objective  
This project aims to improve **DNA enhancer prediction** by utilizing **ensemble learning**, where individual models contribute dynamically based on their accuracy. The final model integrates multiple classifiers to enhance robustness and accuracy.  

## 🛠 Technologies Used  
- **Programming Language:** Python  
- **Machine Learning Models:**  
  - Convolutional Neural Network (**CNN**)  
  - Extreme Gradient Boosting (**XGBoost**)  
  - Random Forest (**RF**)  
  - Stacked Ensemble Model (Neural Network as meta-model)  
- **Tools & Libraries:** TensorFlow, Keras, Scikit-learn, NumPy, Pandas, Matplotlib  

## 📂 Repository Structure  
Projects/ 
│── Dynamic_Ensemble_DNA_Enhancer_Colab.ipynb # Google Colab notebook 
│── data/ # Dataset files  
│── models/ # Saved trained models  
│── results/ # Performance metrics and reports 
│── LICENSE # License file 
│── README.md # Project documentation

## 📈 Key Features  
✔️ **Preprocessing DNA sequences** using One-Hot Encoding and CountVectorizer  
✔️ **Balancing dataset** using **SMOTE** to handle class imbalance  
✔️ **Implementation of multiple models** for enhancer classification  
✔️ **Stacking ensemble** approach to integrate predictions dynamically  
✔️ **Evaluation using accuracy, F1-score, precision, and recall**  

## 📊 Results  
The stacked ensemble model achieves **higher accuracy** than individual models:  

| Model          | Accuracy | Precision | Recall | F1 Score |  
|---------------|----------|-----------|--------|---------|  
| CNN           | 91.33%   | 94.47%    | 95.47% | 94.97%  |  
| XGBoost       | 89.45%   | 96.30%    | 91.19% | 93.68%  |  
| Random Forest | 90.57%   | 96.05%    | 92.82% | 94.41%  |  
| **Stacked Model** | **92.40%** | **94.84%** | **96.38%** | **95.60%** |  

---

## ⚖️ License  
**© Chandana V 2025. All Rights Reserved.**  
This project is made available for **viewing purposes only**. **Any use, modification, distribution, or reproduction is strictly prohibited** without prior written consent from the author.  

---

## 💡 Future Enhancements  
- Integrating **Transformer-based models (e.g., DNABERT)** for improved accuracy  
- Exploring **attention mechanisms** to enhance feature extraction  
- Optimizing model performance using **hyperparameter tuning**  

---

⭐ **Feel free to explore the project!** If you have any questions, reach out to me. 😊  
