# 🐞 Smart Bug Tracking and Predicting System (Advanced Version)

## 📌 Project Overview

The **Smart Bug Tracking and Predicting System** is a Machine Learning-based application designed to automate bug management in software development. It predicts **bug severity**, **priority**, and detects **duplicate bugs** using Natural Language Processing (NLP) techniques.

The system also includes an **interactive web dashboard** built with Gradio, enabling real-time bug submission, tracking, and analysis.

---

## 🎯 Objectives

* Automate bug severity classification
* Predict bug priority levels
* Detect duplicate bug reports
* Provide a user-friendly bug tracking dashboard
* Reduce manual effort in bug triaging

---

## ⚙️ Features

* ✅ Automatic bug dataset generation (600+ records)
* ✅ Text preprocessing using NLP techniques
* ✅ TF-IDF feature extraction
* ✅ Multiple ML models (SVM, Naive Bayes, Random Forest)
* ✅ Severity & Priority prediction
* ✅ Duplicate bug detection using cosine similarity
* ✅ Bug tracking system with history
* ✅ Search and filtering functionality
* ✅ Interactive web interface using Gradio
* ✅ Model comparison and accuracy visualization

---

## 🧠 Technologies Used

| Category             | Tools/Technologies |
| -------------------- | ------------------ |
| Programming Language | Python             |
| Environment          | Google Colab       |
| Machine Learning     | Scikit-learn       |
| NLP                  | NLTK               |
| Visualization        | Matplotlib         |
| Web Interface        | Gradio             |

---

## 🏗️ System Architecture

```
Automatic Bug Dataset Generator
           │
           ▼
Text Preprocessing (NLP Cleaning)
           │
           ▼
TF-IDF Feature Extraction
           │
           ▼
Machine Learning Models
(SVM | Naive Bayes | Random Forest)
           │
           ▼
Bug Severity & Priority Prediction
           │
           ▼
Duplicate Bug Detection
           │
           ▼
Web Dashboard (Gradio)
```

---

## 🔄 Workflow

1. Generate synthetic bug dataset
2. Clean and preprocess text data
3. Convert text into numerical features using TF-IDF
4. Train ML models for classification
5. Predict severity and priority of bugs
6. Detect duplicate bugs using similarity measures
7. Display results in an interactive dashboard

---

## 📊 Model Performance

| Model         | Accuracy |
| ------------- | -------- |
| SVM           | ~88%     |
| Naive Bayes   | ~85%     |
| Random Forest | ~92%     |

* **Best Model:** Random Forest
* **Overall System Accuracy:** ~90–92%

---

## 🚀 How to Run the Project (Google Colab)

1. Open Google Colab
2. Copy and paste the complete source code
3. Install required libraries:

   ```python
   !pip install nltk gradio scikit-learn
   ```
4. Run all cells step by step
5. Launch the Gradio interface
6. Submit bug details and view predictions

---

## 💻 Usage

### Submit Bug

* Enter bug title and description
* Get predicted severity, priority, and duplicate status

### View Bugs

* View all submitted bugs in tabular format

### Search Bugs

* Search bugs using keywords

### Duplicate Detection

* Identify similar bugs automatically

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score

---

## ⚠️ Limitations

* Uses synthetic dataset (may not reflect real-world complexity)
* TF-IDF does not capture deep semantic meaning
* Duplicate detection is threshold-based

---

## 🔮 Future Enhancements

* Use **BERT / Deep Learning models** for better NLP
* Integrate with **GitHub / Jira APIs**
* Add **bug assignment system**
* Use **MongoDB / SQL database** for scalability
* Develop full-stack web application

---

## 🌍 Real-World Applications

* Software development companies
* DevOps teams
* Automated issue tracking systems
* QA testing environments

---

## 👨‍💻 Author

**Kishorekumar Babu**

---

## 📌 Conclusion

This project demonstrates how **Machine Learning and NLP** can be effectively used to automate software bug tracking and improve development efficiency. It provides a scalable foundation for building real-world intelligent bug management systems.

---
