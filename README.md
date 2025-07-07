# 📊 Decision Tree Regression

This project demonstrates a **basic implementation of Decision Tree Regression** to predict salaries based on position levels. It uses a simple logic-based approach without using machine learning libraries like `scikit-learn`.

---

## 📁 Dataset Details

- File used: `Position_salaries.xlsx.csv`
- Contains 3 columns:
  - `Position`: Job title (e.g., Business Analyst, Manager)
  - `Level`: Numeric level for each job
  - `Salary`: Corresponding salary for each level

---

## 📌 Project Workflow

1. **📥 Import Libraries**  
   Imported basic libraries like `pandas` for data handling and `matplotlib` for plotting.

2. **📊 Load Dataset**  
   Dataset is read using `pandas.read_csv()`.

3. **🧩 Split Features and Target**  
   - **X**: Independent feature → `Level`  
   - **y**: Target variable → `Salary`

4. **🧮 Decision Logic (Regression)**  
   - Instead of using a model, a simple decision logic or condition-based method is applied to predict values from the data.

5. **🔮 Prediction**  
   - A user-defined input level is given, and the matching or closest salary is predicted.

6. **📈 Visualization**  
   - Data is visualized using `matplotlib` to show how decision values are mapped.

7. **🎯 User Input**  
   - Code allows user input for level, then returns predicted salary based on logic.

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `pandas`
  - `matplotlib`

---
