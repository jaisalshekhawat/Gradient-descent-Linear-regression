# 📈 Linear Regression from Scratch using Mini-Batch Gradient Descent

## 🚀 Overview

This project implements **Linear Regression from scratch** using **Mini-Batch Gradient Descent** without relying on built-in machine learning models.

The goal is to deeply understand how optimization works in machine learning by manually implementing the training process, including gradient computation, parameter updates, and convergence behavior.

---

## 🧠 Key Concepts Covered

* Linear Regression Model
* Gradient Descent Optimization
* Mini-Batch Gradient Descent
* Feature Scaling (Standardization)
* Target Normalization (Z-score)
* Loss Function (Mean Squared Error)
* Model Evaluation (R² Score, MAE)

---

## ⚙️ Approach

1. **Data Preprocessing**

   * Handled categorical variables using one-hot encoding
   * Converted dataset to numerical format

2. **Feature Scaling**

   * Standardized input features using mean and standard deviation

3. **Target Normalization**

   * Applied Z-score normalization to stabilize training

4. **Model Implementation**

   * Initialized weights and bias
   * Implemented Mini-Batch Gradient Descent:

     * Forward pass
     * Gradient computation
     * Parameter updates

5. **Training**

   * Iteratively minimized loss using gradient descent
   * Observed convergence using loss curve

---

## 📉 Loss Function

Mean Squared Error (MSE):

[
Loss = \frac{1}{n} \sum (y - y_{pred})^2
]

---

## 📊 Results

* **R² Score:** ~0.97
* **MAE:** Very low error
* Smooth convergence observed in loss curve

---

## 📈 Training Visualization

The model shows:

* Rapid initial learning
* Stable convergence
* No divergence or instability

---

## 🧪 Comparison with Library Model

The custom implementation was validated against `scikit-learn`’s Linear Regression model, showing comparable performance.

---

## 🛠️ Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 📁 Project Structure

```
lr-gradient-descent/
│
├── Linear_Regression_from_Scratch_using_Mini_Batch_Gradient_Descent.ipynb
├── README.md
```

---

## 🎯 Key Learnings

* Importance of feature scaling in optimization
* How gradients influence learning
* Effect of learning rate on convergence
* Difference between batch, stochastic, and mini-batch gradient descent

---

## 🔥 Future Improvements

* Implement Adam Optimizer
* Add Regularization (L1/L2)
* Convert notebook into modular Python package
* Deploy as a simple ML API

---

## 💡 Conclusion

This project demonstrates a deep understanding of **machine learning fundamentals** by building a model from scratch, rather than relying solely on libraries.

---

## 👤 Author

**Jaisal Shekhawat**

---

## ⭐ If you like this project

Give it a star on GitHub!
