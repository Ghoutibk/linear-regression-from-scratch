# Linear Regression From Scratch 🧮

## 📌 Project Overview
This project demonstrates the implementation of a **Linear Regression model from the ground up**, without relying on high-level predictive libraries like Scikit-Learn. 

The goal was to translate the underlying mathematics of Machine Learning into clean, functional Python code using **Object-Oriented Programming (OOP)** and **Vectorization**.

## 🚀 Key Features
* **Built from Scratch:** Custom implementation of the training loop and prediction logic.
* **Vectorized Gradient Descent:** Replaced slow `for` loops with optimized matrix multiplications using NumPy (`np.dot`).
* **Object-Oriented Design:** Encapsulated the algorithm within a reusable Python class (`Linear_Regression`).
* **Mathematical Foundation:** Implemented the exact mathematical formulas for weight updates and cost calculation.

## 🛠️ Tech Stack
* **Python 3**
* **NumPy:** For matrix operations and vectorized calculations.
* **Pandas:** For data ingestion and manipulation.
* **Matplotlib:** For visualizing the cost function and the final regression line.

## 📊 Results & Visualization
The model was trained on a dataset to predict salary based on years of experience. After 1000 iterations with a learning rate of 0.02, the Gradient Descent successfully converged.

<img width="1146" height="902" alt="image" src="https://github.com/user-attachments/assets/46560245-e2cb-402e-828e-22e7d6cb0e00" />



## 🧠 The Math Behind the Code
The core of the weight update is based on the vectorized Gradient Descent formula:
`w = w - learning_rate * dw`
Where `dw` is the derivative of the cost function with respect to the weights.
