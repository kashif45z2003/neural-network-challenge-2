# neural-network-challenge-2

## Neural Network for Employee Attrition and Department Prediction

## 📌 Overview

This project uses a branched neural network built with TensorFlow/Keras to predict:

- Whether an employee is likely to leave the company (**attrition**)
- Which department best fits them

## 🧠 Model Design

- Two output branches (multi-output model)
- Preprocessing includes one-hot encoding and feature scaling
- Separate branches for attrition and department predictions using softmax activation

## 📊 Dataset

- [Attrition Dataset](https://static.bc-edx.com/ai/ail-v-1-0/m19/lms/datasets/attrition.csv)
- Includes features such as education, job satisfaction, work-life balance, and more

## 🧪 Evaluation Results

Final model accuracy:

- Attrition prediction: **~54.6%**
- Department prediction: **~79.3**

## ⚙️ Tools & Technologies

- Python, Pandas, NumPy
- Scikit-learn for preprocessing
- TensorFlow / Keras for modeling

## 📁 Files

- `attrition.ipynb`: The main notebook containing preprocessing, model creation, training, and evaluation
- `README.md`: This file

## 🙋‍♂️ Author

Kashif Zafar  
Ohio State University Coding Bootcamp  
