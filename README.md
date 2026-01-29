# Linear Regression from Scratch using Python

This project implements **Simple Linear Regression from scratch** using Python and NumPy.  
The goal is to understand how linear regression works internally by manually implementing
feature normalization, cost calculation, and gradient descent — without using any ML libraries.

---

## 📊 Dataset
- Dataset: Salary vs Years of Experience
- Input Feature: Years of Experience
- Target Variable: Salary

---

## ⚙️ Steps Implemented

### 1️⃣ Data Loading
- Loaded CSV data using Pandas
- Extracted feature (X) and target (y) values

### 2️⃣ Data Visualization
- Plotted original data to observe the linear relationship between experience and salary

---

### 3️⃣ Feature Normalization
Implemented normalization manually using mean and variance:

- Mean calculation
- Variance calculation
- Standard score normalization  

This helps gradient descent converge faster.

---

### 4️⃣ Linear Regression Model (From Scratch)

A custom `SimpleLR` class is implemented with:

- Random initialization of weight and bias
- Prediction function  
- Manual gradient descent optimization
- Mean Squared Error loss function
- Early stopping using loss difference threshold

---

### 5️⃣ Cost Function
Mean Squared Error (MSE) is used:

J(w, b) = (1 / 2n) * Σ(y − ŷ)²

---

### 6️⃣ Gradient Descent
- Weight and bias updated iteratively
- Learning rate and maximum iterations configurable
- Training stops when loss improvement falls below a threshold

---

### 7️⃣ Model Training
- Model trained using normalized input feature
- Loss values stored for each iteration
- Convergence visualized using loss vs iterations plot

---

### 8️⃣ Model Evaluation & Visualization
- Plotted regression line over actual data
- Visual confirmation of model fitting

---

## 📈 Results
- Loss decreases smoothly, showing successful convergence
- Final regression line closely fits the data points

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📂 Project Structure
- `Linear_Regression.ipynb` → Complete implementation with explanations and plots

---

## 🚀 Learning Outcomes
- Understood gradient descent mechanics
- Learned why feature scaling is important
- Gained insight into loss minimization
- Built linear regression without external ML libraries

---

## 🔮 Future Improvements
- Add Multiple Linear Regression
- Compare with scikit-learn implementation
- Add evaluation metrics like R² score
- Extend to Polynomial Regression
