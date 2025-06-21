# 📈 Simple Linear Regression with NumPy and Matplotlib

This project demonstrates a basic implementation of **linear regression** using **NumPy** for calculations and **Matplotlib** for visualizations — all written and executed in **Google Colab**.

---

## 🚀 Project Overview

We predict housing prices based on house sizes (in 1000 square feet). It follows these key steps:

- Data setup and visualization
- Hypothesis: `f(x) = w * x + b`
- Model output computation
- Graphical comparison between **actual values** and **predicted values**

---

## 📊 Sample Data Used

```python
x_train = [1, 2, ..., 10]   # House size in 1000 sqft
y_train = [2, 4, ..., 20]   # Price in 1000s of dollars
```
This represents a perfect linear relationship where the house price doubles the size.

## 🧠 Model Function
f(x) = w * x + b
You can modify w (weight) and b (bias) to observe how predictions change.

## 📌 Features
Simple and beginner-friendly implementation

Line plot of predicted prices over actual data

Easy to run in Google Colab

Includes manual prediction (e.g., cost for a 1200 sqft house)

## 🖼️ Visualization
The project generates plots to visualize:

Actual vs Predicted house prices

Effect of different weights (w) and biases (b)

## 📦 Dependencies
Python 3.x

NumPy

Matplotlib

Install using:

pip install numpy matplotlib

## 📁 Running the Notebook
You can run this directly on Google Colab by clicking the badge below:


## 🧪 Example Prediction
w = 200
b = 100
x = 1.2  # 1200 sqft
Prediction: $340,000

## 📬 Author
### Karthik Aljapur


⭐️ Star this repository if you found it helpful!
