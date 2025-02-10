# Logistic Regression Model for DMV Test Data

## 📌 Project Overview

This project implements a **Logistic Regression Model** to predict whether a candidate will pass or fail the **DMV Written Test** based on their scores from two written exams. The model is trained using **gradient descent** and evaluated through cost function analysis and decision boundary visualization.

## 📂 Files in This Repository

- `logistic_regression.ipynb` - Jupyter Notebook containing the complete implementation.
- `DMV_Written_Tests.csv` - Dataset containing the candidates' test scores.
- `cost_function_over_iterations.png` - Graph showing cost function convergence.
- `README.md` - Project documentation (this file).

## 🚀 Features Implemented

- Data visualization using **Seaborn & Matplotlib** 📊
- Implementation of the **Sigmoid function** ⚡
- Cost function computation (Log Loss) 📉
- Gradient Descent for model optimization 🔄
- Decision boundary visualization ✨
- Model accuracy evaluation 📈
- Predicting outcomes for new candidates 🎯

## 🔬 Key Functions Explained

- **`logistic_function(x)`** → Implements the sigmoid activation function.
- **`compute_cost(theta, x, y)`** → Computes the cost function (Log Loss) and its gradient.
- **`gradient_descent(x, y, theta, alpha, iterations)`** → Optimizes the model parameters using gradient descent.
- **`predict(theta, x)`** → Predicts outcomes based on trained weights.

## 📷 Visualizations

- **Scatter plot** of test scores with pass/fail markers.
- **Cost function convergence** over iterations.
- **Decision boundary** separating passing and failing candidates.

## 💡 Future Improvements

- Implement **regularization** to prevent overfitting.
- Test with **larger datasets** for improved generalization.
- Explore alternative **optimization algorithms**.

---

**🔗 Author: [Cenuse Flavius]**  
🚀 Connect with me on [LinkedIn](https://www.linkedin.com/in/flavius-cenuse/)  
🐍 Follow me on [GitHub](https://github.com/Flav-Flavius)
