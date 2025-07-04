# Spam-Mail-Prediction
📧 Spam Mail Detection using Machine Learning  This project uses Machine Learning to detect spam emails based on their content.
---

## 📁 Dataset

- CSV file: `mail_data.csv`  
- Columns:  
  - `Category` (spam or ham)  
  - `Message` (text of the email)
---

## 🔍 Project Overview

- ✅ Preprocessing real-world email data
- ✂️ Removing null values and encoding labels
- 🧠 Using **TF-IDF Vectorization** to convert text into numerical features
- 🤖 Training a **Logistic Regression** model
- 📊 Evaluating performance using **accuracy** and **confusion matrix**
- ⌨️ Creating a simple **prediction system** where users input email content
  ---


  ## 🧠 Model Used

- **Logistic Regression** for binary classification
- Achieved:
  - ✅ **Accuracy on training data:** 96.77%
  - ✅ **Accuracy on test data:** 96.68%

    ---
    ## 🧾 Code Structure

1. **Importing libraries**  
   – `pandas`, `sklearn`, `TfidfVectorizer`, `LogisticRegression`, etc.

2. **Data Loading & Preprocessing**  
   – Load `mail_data.csv`  
   – Replace missing values with empty strings  
   – Encode `spam` as `0`, `ham` as `1`  

3. **Splitting the Dataset**  
   – Train/test split (80% / 20%)  

4. **Feature Extraction**  
   – Apply **TF-IDF Vectorization** to convert emails into numerical form  

5. **Model Training**  
   – Train a **Logistic Regression** model using the feature vectors  

6. **Model Evaluation**  
   – Predict on both training and test data  
   – Print accuracy and show the **confusion matrix** using `seaborn`  

7. **Prediction System**  
   – Allow the user to input an email and predict if it's **spam or ham**

---

## 🔗 Run on Google Colab

👉 [Click here to open the notebook in Colab](https://colab.research.google.com/drive/10ZbbZZUc-Vb8uWWXNU6uGSsFCj3wqb5U?usp=sharing)

---
## 👩‍💻 Author

**Aidaoui Yousra Chahinez**

