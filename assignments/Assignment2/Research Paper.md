# Predicting Student Performance Using Academic Data

## Project Overview
This project applies Machine Learning concepts to predict student academic performance based on student information and learning behavior. The goal is to determine whether a student will have **Poor, Average, Good, or Excellent** performance using academic and demographic data.

This is a **Supervised Machine Learning Classification** problem.

---

# Problem Statement
Educational institutions need to identify students who may require additional academic support. Predicting student performance helps teachers and schools provide early intervention, improve learning outcomes, and support student success.

This project aims to build a Machine Learning model that predicts a student's overall performance based on academic and personal factors.

---

# Dataset Description

* **Total Samples:** 50 students
* **Features:** 9
* **Label:** 1

Each row represents one student.

---

# Features (X)

* Student_ID *(Identifier only)*
* Gender
* Age
* Study_Hours_Per_Day
* Attendance (%)
* Parent_Education
* Internet_Access
* Assignment_Score
* Final_Exam_Score

---

# Label (y)

**Performance**

* Poor
* Average
* Good
* Excellent

**Student_ID** is used only as an identifier and is **not** used as a model feature.

---

# Sample Data

| Student_ID | Gender | Age | Study Hours | Attendance (%) | Parent Education | Internet Access | Assignment Score | Final Exam Score | Performance |
| ---------- | ------ | --- | ----------- | -------------- | ---------------- | --------------- | ---------------- | ---------------- | ----------- |
| ST001      | Female | 20  | 3           | 90             | University       | Yes             | 82               | 85               | Good        |
| ST002      | Male   | 22  | 1           | 65             | Secondary        | No              | 58               | 55               | Poor        |
| ST003      | Female | 21  | 4           | 95             | University       | Yes             | 90               | 92               | Excellent   |

---

# Machine Learning Type

**Type:** Supervised Learning  
**Task:** Classification

The model learns from labeled student data and predicts whether a student's performance will be **Poor, Average, Good, or Excellent**.

---

# Data Quality Notes

The dataset is generally suitable for Machine Learning but contains a few issues that require preprocessing:

* Missing values in Attendance and Assignment Score
* Inconsistent categorical values (e.g., **Yes**, **yes**, **YES**)
* Different feature scales (study hours, attendance, exam scores)
* Encoding required for categorical variables
* Student_ID should be removed before model training because it is only an identifier

These issues will be handled during the data preprocessing stage.

---

# Use Case

This model can be used to:

* Predict student academic performance
* Identify students who need academic support
* Help teachers monitor student progress
* Improve educational planning and decision-making

---

# Data Science Workflow

1. Problem Definition
2. Data Collection
3. Data Understanding
4. Data Preprocessing
5. Feature Engineering
6. Model Training
7. Model Evaluation
8. Deployment

---

# Conclusion

This project demonstrates how student academic data can be used to predict student performance using Machine Learning. The dataset contains **50 student records** and is suitable for a **Supervised Classification** problem.

Future work includes data cleaning, preprocessing, feature engineering, model training, and evaluating different classification algorithms to improve prediction accuracy.
