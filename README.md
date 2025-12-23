# Student Performance Prediction using Machine Learning

## Project Overview
This project predicts whether a student will **pass or fail** based on their study hours, attendance, and previous marks using a **Logistic Regression** model.  

It demonstrates **data preprocessing, model training, evaluation, and visualization** of results using Python libraries.

---

## Dataset
- **Columns**:
  - `study_hours` → Number of hours the student studies daily
  - `attendance` → Attendance percentage
  - `previous_marks` → Marks scored in the previous exam
  - `result` → Target variable: `pass` or `fail`
- Example dataset: `student_data.csv`

---

## Features Used
1. Study Hours  
2. Attendance  
3. Previous Marks  

---

## Model
- **Algorithm**: Logistic Regression  
- **Evaluation**:
  - **Accuracy**: Displays how well the model predicts pass/fail
  - **Confusion Matrix**: Visualizes correct vs incorrect predictions

### Confusion Matrix Example
![Confusion Matrix](confusion_matrix.png)  
> Replace `confusion_matrix.png` with your actual screenshot.

- **Feature Graphs**: Show how each factor affects the outcome

### Feature Graphs Example
![Feature Graphs](feature_graphs.png)  
> Replace `feature_graphs.png` with your actual screenshot.

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/Khushiiii002/student_performance_prediction.git
```
2. Install required Python libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib
   ```
3. Run the Python script:
```bash
python student_performance.py
```
**Output includes**:
-`Model accuracy printed in the console`
-`Confusion matrix graph`
-`Feature distribution graphs`

**Tools & Libraries**
-`Python`
-`Pandas`
-`NumPy`
-`scikit-learn`
-`Matplotlib`

**Author**
Khushi Sheth
GitHub: https://github.com/Khushiiii002
