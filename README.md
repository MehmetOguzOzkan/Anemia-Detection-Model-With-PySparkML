# 🩸 Anemia Detection Model with PySparkML

This project leverages Apache Spark's powerful **PySparkML** library to build a scalable and efficient machine learning pipeline for detecting **Anemia** based on health-related attributes. It demonstrates end-to-end big data processing, feature engineering, and classification in a distributed computing environment.

---

## 📊 Overview

Anemia is a common blood disorder that affects the oxygen-carrying capacity of red blood cells. Early and accurate detection is crucial for timely treatment.

This project provides:

- A **machine learning model** that classifies whether a patient has anemia.
- A full **PySpark ML pipeline** including data preprocessing, feature transformation, and model training.
- **Scalable** processing of large health datasets.

---

## 🧠 Machine Learning Pipeline

The PySpark ML pipeline consists of the following stages:

1. **Data Loading** – Load dataset using Spark DataFrames.
2. **Data Cleaning** – Handle nulls, drop irrelevant features.
3. **Feature Engineering** – VectorAssembler, StringIndexer, and feature scaling.
4. **Model Training** – Train a Logistic Regression model.
5. **Evaluation** – Use accuracy, precision, recall, F1 score.

---

## 🧪 Technologies Used

Plain text: PySpark, Spark MLlib, Pandas, Matplotlib, Scikit-learn, Jupyter Notebook

---

## 📈 Model Performance

Key evaluation metrics on test set:

| Metric     | Score  |
|------------|--------|
| Accuracy   | 0.91   |
| Precision  | 0.89   |
| Recall     | 0.93   |
| F1 Score   | 0.91   |

> 💡 These values may vary slightly based on dataset size and preprocessing.

---

## 🧬 Sample Dataset Attributes

| Feature              | Description                      |
|----------------------|----------------------------------|
| Age                  | Age of the patient               |
| Hemoglobin Level     | Blood hemoglobin concentration   |
| RBC Count            | Red blood cell count             |
| MCV                  | Mean Corpuscular Volume          |
| Anemia               | Target variable (Yes/No)         |

---

## 🚀 How to Run

1. Clone the repository  
   
bash
   git clone https://github.com/MehmetOguzOzkan/Anemia-Detection-Model-With-PySparkML.git
   cd Anemia-Detection-Model-With-PySparkML
2. Launch Jupyter Notebook
bash
   jupyter notebook anemia_model.ipynb
3. Install dependencies
   
bash
   pip install pyspark
4. Run the notebook cell by cell and observe the output.
   
## 📚 Future Work

- [ ] Integrate additional ML models (Random Forest, Gradient-Boosted Trees)
- [ ] Deploy model using Spark Streaming for real-time detection
- [ ] Build a simple UI for user-friendly anemia prediction

---

## 👨‍💻 Author

**Mehmet Oğuz Özkan**  
📧 Email: [mehmetoguzozkan@gmail.com](mailto:mehmetouz9921@gmail.com)
[💻 GitHub](https://github.com/MehmetOguzOzkan)

---

## ⭐️ Give a Star

If you found this project useful, consider giving it a ⭐️ on [GitHub](https://github.com/MehmetOguzOzkan/Anemia-Detection-Model-With-PySparkML)!

---
