# KNN Classification on Iris Dataset

## 📌 Objective
This project applies the **K-Nearest Neighbors (KNN)** algorithm to the classic **Iris dataset**.  
The goal is to classify iris flower species based on sepal and petal measurements.

---

## 📊 Steps Performed
1. **Data Loading**: Loaded `Iris.csv` dataset.
2. **Preprocessing**: Normalized features using `StandardScaler`.
3. **Model Training**: Applied `KNeighborsClassifier` with different K values.
4. **Evaluation**: Used accuracy and confusion matrix for performance measurement.
5. **Visualization**: Plotted decision boundaries and accuracy vs. K.

---

## 🖼️ Results
- **Best Accuracy**: Found at K = 5  
- **Confusion Matrix**: Shows good separation between species.  
- **Decision Boundary**: Visualizes how KNN separates classes using Sepal Length & Width.

Screenshots are available in the `screenshots/` folder.

---

## ⚙️ Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/KNN-Iris-Classification.git
