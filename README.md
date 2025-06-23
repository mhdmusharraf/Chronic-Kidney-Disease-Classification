# 📊 Classification Assignment

This project focuses on building and evaluating various classification models on a dataset with **399 rows** and **25 columns** using **binary classification** techniques. The objective is to select the best-performing model for deployment.

---

## 🧠 Machine Learning Pipeline

1. **Stage 1: Machine Learning**
   - Numerical inputs are used.
2. **Stage 2: Supervised Learning**
   - Both inputs and outputs are known.
3. **Stage 3: Binary Classification**
   - Output is in Yes/No format.

---

## 📁 Dataset Information

- **Total Rows:** 399
- **Total Columns:** 25
- **Preprocessing:**
  - **One-Hot Encoding** was applied to convert categorical string data into numerical format.

---

## 🧪 Algorithms Used & Results

| Model                  | Overall Performance |
|------------------------|---------------------|
| Logistic Regression    | 0.99                |
| SVM Classification     | 0.99                |
| KNN Classifier         | 0.97                |
| BernoulliNB            | 0.98                |
| GaussianNB             | 0.98                |
| Decision Tree          | 0.98                |
| Random Forest          | 0.98                |
| MultinomialNB          | 0.89                |
| ComplementNB           | 0.89                |

---

## ✅ Final Model Selection

Both **Logistic Regression** and **SVM Classification** achieved an overall accuracy of **0.99**. However, **Logistic Regression** was chosen for deployment due to:

- **Better Interpretability**: Model coefficients are easy to understand.
- **Faster Inference**: Lightweight and efficient in real-time applications.
- **Simplicity**: Less complex compared to kernel-based SVM.
- **Lower Risk of Overfitting**: More robust on structured data.

---

## 🚀 Deployment Recommendation

Deploy the **Logistic Regression** model as the final model for production use. It balances performance, interpretability, and maintainability effectively.

---

## 📌 Tools & Libraries Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn (for visualizations, if used)

---

