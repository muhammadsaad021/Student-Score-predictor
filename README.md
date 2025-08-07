# 🧠 Student Score Predictor

This project uses a **Linear Regression** model to predict student exam scores based on a variety of performance-related factors.

The dataset is sourced from [Kaggle's Student Performance Factors](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors) and includes attributes such as hours studied, attendance, parental involvement, motivation level, and more.

---

## 📊 Features Used

The following features were used to predict student performance:

- Hours_Studied  
- Attendance  
- Parental_Involvement  
- Access_to_Resources  
- Extracurricular_Activities  
- Sleep_Hours  
- Previous_Scores  
- Motivation_Level  
- Internet_Access  
- Tutoring_Sessions  
- Family_Income  
- Teacher_Quality  
- School_Type  
- Peer_Influence  
- Physical_Activity  
- Learning_Disabilities  
- Parental_Education_Level  
- Distance_from_Home  
- Gender  
- Exam_Score (Target)

All categorical features were **one-hot encoded** prior to training and the feature count comes to a total of 41.

---

## 🧪 Model Used

- **Linear Regression** (from `sklearn.linear_model`)
- Data preprocessed using `pandas` and `scikit-learn`

---

## 🚀 How to Use

1. **Clone or download this repository**.
2. **Open the provided Google Colab notebook**.
3. **Upload the dataset**:
   - Download the dataset file `StudentPerformanceFactors.csv` (attached in this repo).
   - In Colab, upload it.
4. The notebook will handle data preprocessing, model training, and evaluation.

---

## 📁 Dataset

The dataset file `StudentPerformanceFactors.csv` is included in this repository.

If you want to download it directly from Kaggle:  
[Kaggle's Student Performance Factors](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)

---

## 🧠 Motivation

Understanding how various academic, social, and personal factors influence student performance can help educators and policymakers better support learners.

---

## 📌 Requirements

- Python 3.x
- pandas
- scikit-learn
- numpy
- Google Colab (recommended)

---

## 📜 License

This project is for educational and research purposes only. Refer to the original dataset’s license on Kaggle for data usage rights.

---

## 👤 Author

Muhammad Saad  
GitHub: [@muhammadsaad021](https://github.com/muhammadsaad021)


