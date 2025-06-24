# Student-Performance-Prediction-Data-Mining
The goal of this project is to predict student academic performance based on various factors using data mining techniques. Accurate prediction models can help educational institutions provide early interventions and support for students at risk of underperforming.
Absolutely! Here's a clean and professional **`README.md`** content you can use for your GitHub repository for the **Student Performance Prediction** project:

# 🎓 Student Performance Prediction

This project uses data mining and machine learning techniques to predict students' academic performance based on demographic, social, and academic factors. It is built using Python and the UCI Student Performance Dataset.

---

## 📁 Dataset

- **Source**: [UCI Machine Learning Repository – Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- **File Used**: `student-mat.csv` (Math course)
- **Records**: 395 students
- **Features**: 33 (school, gender, age, study time, absences, grades, etc.)
- **Target**: Final grade `G3` (converted into categories: Low, Medium, High)

---

## 🧠 Objectives

- Clean and preprocess raw student data.
- Convert numerical target (`G3`) into classification labels.
- Apply classification algorithms to predict performance categories.
- Visualize most important influencing features.
- Evaluate model performance using appropriate metrics.

---

## 🧰 Tools and Libraries

- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-performance-prediction.git
   cd student-performance-prediction
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook StudentPerformancePrediction.ipynb
   ```

---

## 🧪 Models Used

* **Decision Tree Classifier**
* **Random Forest Classifier**

Performance is evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report

---

## 📊 Feature Importance

Feature importance was visualized to determine which attributes most affect final student performance. Key features:

* G1 and G2 grades
* Failures
* Absences
* Study time
* Parental education

---

## 📈 Results Summary

* The models successfully classified students into performance levels (Low, Medium, High).
* Random Forest performed slightly better than Decision Tree.
* G1, G2, and attendance-related features were most predictive.

---

## 📌 Future Improvements

* Try additional classifiers (SVM, XGBoost)
* Include dropout prediction as a separate task
* Build a Streamlit or Flask web app interface

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🤝 Acknowledgments

* UCI Machine Learning Repository
* scikit-learn documentation

```

---

Let me know if you'd like a `requirements.txt` or a sample `StudentPerformancePrediction.ipynb` file to go along with it!
```
