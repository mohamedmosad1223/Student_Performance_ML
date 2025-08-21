# student_performance_prediction
Project Description
This project analyzes student data to predict **final exam score** using Machine Learning techniques.  
It explores how different features (study hours, attendance, parental education, pass fail , etc.) affect student outcomes.  

---

## 📂 Dataset
- Number of students: ~500  
- Features:  
  - Study hours per week  
  - Attendance rate  
  - Past exam scores  
  - Parental education level  
  - Internet access at home  
  - Extracurricular activities  

---

## 🛠️ Tools & Libraries
- **Python**  
- **Pandas, NumPy** for data processing  
- **Matplotlib, Seaborn** for visualization  
- **Scikit-learn** for ML models (Linear Regression, Random Forest)  

---

## 🚀 Workflow
1. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions & correlations  
   - Detected outliers & missing values  

2. **Data Preprocessing**  
   - Label Encoding categorical features  
   - Feature scaling where needed  

3. **Model Training**  
   - Linear Regression  
   - Random Forest Regressor  

4. **Evaluation Metrics**  
   - R² Score  
   - Mean Squared Error (MSE)  

---

## 📊 Results
- **Linear Regression** → R² Test = 1.0 
- **Random Forest** → R² Test = 0.99998 ✅  

Random Forest performed significantly better in capturing complex patterns.  

---

## 📜 How to Run
```bash
# Clone the repository
git clone https://github.com/your-username/student-performance-prediction.git

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook student_performance.ipynb
