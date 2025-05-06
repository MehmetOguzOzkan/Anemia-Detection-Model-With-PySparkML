# 🩸 Anemia Detection Model with PySparkML

This project leverages Apache Spark's powerful **PySparkML** library to build a scalable and efficient machine learning pipeline for detecting **Anemia** based on health-related attributes. It demonstrates end-to-end big data processing, feature engineering, and classification in a distributed computing environment.

---

## 📊 Overview

Anemia is a common blood disorder that affects the oxygen-carrying capacity of red blood cells. Early and accurate detection is crucial for timely treatment.

**This project provides:**

- ✅ A **machine learning model** that classifies whether a patient has anemia  
- ✅ A complete **PySpark ML pipeline** including data preprocessing, feature transformation, and model training  
- ✅ **Scalable** processing of large health datasets  

---

## 🧠 Machine Learning Pipeline

The PySpark ML pipeline consists of the following stages:

1. 🔹 **Data Loading** – Load dataset using Spark DataFrames  
2. 🔹 **Data Cleaning** – Handle nulls, drop irrelevant features  
3. 🔹 **Feature Engineering** – Apply `VectorAssembler`, `StringIndexer`, and scaling  
4. 🔹 **Model Training** – Train a Logistic Regression model  
5. 🔹 **Evaluation** – Use accuracy, precision, recall, and F1 score  

---

## 🧪 Technologies Used

**Plain text:** PySpark, Spark MLlib, Pandas, Matplotlib, Scikit-learn, Jupyter Notebook

---

## 📈 Model Performance

<table align="center">
  <thead>
    <tr>
      <th>Metric</th>
      <th>Score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Accuracy</td>
      <td align="center">0.91</td>
    </tr>
    <tr>
      <td align="center">Precision</td>
      <td align="center">0.89</td>
    </tr>
    <tr>
      <td align="center">Recall</td>
      <td align="center">0.93</td>
    </tr>
    <tr>
      <td align="center">F1 Score</td>
      <td align="center">0.91</td>
    </tr>
  </tbody>
</table>

> 💡 These values may vary slightly depending on preprocessing and dataset distribution.

---

## 🧬 Sample Dataset Attributes

<table align="center">
  <thead>
    <tr>
      <th>Feature</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Age</td>
      <td align="center">Age of the patient</td>
    </tr>
    <tr>
      <td align="center">Hemoglobin Level</td>
      <td align="center">Blood hemoglobin concentration</td>
    </tr>
    <tr>
      <td align="center">RBC Count</td>
      <td align="center">Red blood cell count</td>
    </tr>
    <tr>
      <td align="center">MCV</td>
      <td align="center">Mean Corpuscular Volume</td>
    </tr>
    <tr>
      <td align="center">Anemia</td>
      <td align="center">Target variable (Yes/No)</td>
    </tr>
  </tbody>
</table>

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/MehmetOguzOzkan/Anemia-Detection-Model-With-PySparkML.git
   cd Anemia-Detection-Model-With-PySparkML
2. Launch Jupyter Notebook
   ```bash
   jupyter notebook anemia_model.ipynb
3. Install dependencies
   ```bash
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
