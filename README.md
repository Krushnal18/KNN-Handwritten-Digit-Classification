# Task 10: KNN – Handwritten Digit Classification

## 📌 Project Overview
This project implements **K-Nearest Neighbors (KNN)** algorithm to classify handwritten digit images (0–9).  
The objective is to understand distance-based classification and identify the **optimal value of K** using model evaluation.



## 📂 Dataset
- **Dataset Used:** Sklearn Digits Dataset
- Loaded using: `sklearn.datasets.load_digits()`
- Total samples: 1797
- Image size: 8×8 pixels (64 features)

No external dataset (Kaggle/MNIST) was required.



## 🛠 Tools & Libraries
- Python
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook



## 🔑 Methodology
1. Loaded the digits dataset using `load_digits()`
2. Visualized sample digit images to verify labels
3. Split data into training (80%) and testing (20%) sets
4. Applied **StandardScaler** for feature scaling
5. Trained KNN model with initial K = 3
6. Evaluated model accuracy
7. Tested multiple K values (3, 5, 7, 9)
8. Plotted **Accuracy vs K** graph to find best K
9. Generated **Confusion Matrix** to analyze misclassifications
10. Displayed test images with predicted labels



## 📈 Results
- Accuracy with K = 3: ~96.9%
- **Best accuracy achieved at K = 5 (~97.5%)**
- Confusion matrix shows most predictions on the diagonal, indicating strong performance



## ✅ Conclusion
- KNN successfully classified handwritten digits with high accuracy
- Feature scaling improved distance-based learning
- Optimal K value was selected using empirical evaluation
- The project demonstrates a clear understanding of KNN and model evaluation techniques
