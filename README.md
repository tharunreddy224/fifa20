# ⚽ FIFA 20 Player Performance Prediction

## 🧠 Project Overview
This project analyzes the FIFA 20 player dataset to predict player performance levels based on various player attributes such as potential, age, stamina, dribbling, and ball control.  
The project follows the full data science workflow — data preprocessing, exploratory data analysis (EDA), model training, evaluation, and production recommendation.

---

## 📂 Files Included
- `fifa20_cleaned.ipynb` — Main Jupyter Notebook containing the complete analysis, visualizations, and model evaluations.  
- `requirements.txt` — Python dependencies required to run the notebook.  
- `README.md` — This document describing the project and setup instructions.

---

## 🚀 How to Run the Project
1. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Open the Notebook**
   ```bash
   jupyter notebook fifa20_cleaned.ipynb
   ```

3. **Run All Cells**
   - Ensure the dataset (`players_20.csv`) is in the same directory or update the path in the notebook.
   - Execute all cells to reproduce the analysis and results.

---

## 🧩 Models Used
- Logistic Regression  
- Random Forest Classifier  
- Support Vector Machine (SVM)  
- XGBoost Classifier  

Each model was evaluated based on Accuracy, F1-Score, and ROC-AUC to determine the best-performing model.

---

## 🏆 Best Model Recommendation
**Random Forest Classifier** achieved the highest ROC-AUC and balanced performance across all metrics.  
It is recommended for production deployment due to its robustness and interpretability.

---

## 👨‍💻 Author
**Tharun Reddy Nagathi**  
FIFA 20 Machine Learning Project — 2025
