# 🏠 House Price Predictor from Scratch

## 📄 Abstract
This project demonstrates how **Linear Regression** can be implemented *from scratch* using only **NumPy**.  
The goal is to predict house prices based on their size (in square feet) using **gradient descent** for optimization.  
It’s designed as an educational project for students learning the fundamentals of **Machine Learning** and **Mathematics**.

---

## 🎯 Objectives
1. Understand how linear regression works mathematically.
2. Implement gradient descent manually to find the best-fit line.
3. Visualize both training loss and the regression line.
4. Predict house prices for new data points.

---

## 🧩 Dataset
A small, self-created dataset of house sizes (in square feet) and prices (in $1000s):

| Size (sq ft) | Price ($1000s) |
|---------------|----------------|
| 650 | 100 |
| 785 | 120 |
| 900 | 130 |
| 1100 | 150 |
| 1200 | 170 |
| 1400 | 180 |
| 1500 | 195 |

---

## ⚙️ Implementation Details
The project includes:
- **Data Normalization** — to speed up convergence.  
- **Gradient Descent Algorithm** — to update slope and intercept values.  
- **Loss Visualization** — track Mean Squared Error over training epochs.  
- **Regression Line Plot** — visualize predicted vs actual values.  
- **Prediction Step** — estimate price for new house sizes.

---

## 🧮 Core Equations
For a given dataset \( (x_i, y_i) \), the linear model is:

\[ y = mx + b \]

We minimize the Mean Squared Error (MSE):

\[ L = \frac{1}{n} \sum (y_{pred} - y)^2 \]

Gradient Descent updates:
\[ m = m - \alpha \frac{\partial L}{\partial m}, \quad b = b - \alpha \frac{\partial L}{\partial b} \]

---

## 📊 Results
✅ Trained slope and intercept using gradient descent.  
✅ Visualized convergence of loss over epochs.  
✅ Predicted house price for a new sample (e.g., **1300 sq ft**).  

Example Output:
```
Trained parameters: slope=0.732, intercept=0.145
Predicted Price for 1300 sq ft house: $165,480.00
```

---

## 🧠 Learning Outcomes
- Understood the **mathematical intuition** behind linear regression.
- Learned to **implement gradient descent** manually.  
- Understood how **data normalization** affects training speed.
- Created meaningful **visualizations** to interpret the model.

---

## 🧪 Technologies Used
- Python 🐍  
- NumPy  
- Matplotlib  

---

## 🚀 How to Run
1. **Clone this repository**
   ```bash
   git clone https://github.com/<asimsheikh-coder>/house-price-predictor-from-scratch.git
   cd house-price-predictor-from-scratch
   ```
2. **Install dependencies**
   ```bash
   pip install numpy matplotlib
   ```
3. **Run the notebook**
   ```bash
   jupyter notebook Linear_Regression_From_Scratch.ipynb
   ```

---

## 🧑‍💻 Author
**Asim Sheikh**  
12th Grade Student | Aspiring AI Engineer  
📧 Email: asimusmansheikh0@gmail.com  
🌐 GitHub: [@asimsheikh-coder](https://github.com/asimsheikh-coder)

---

## 🔖 Citation
> Usman. *House Price Predictor from Scratch*. 2025. GitHub Repository.  
> [https://github.com/asimsheikh-coder/house-price-predictor-from-scratch](https://github.com/asimsheikh-coder/house-price-predictor-from-scratch)

---

## 🏁 Conclusion
This project is a hands-on introduction to **machine learning** and **data-driven thinking**.  
By building linear regression from scratch, students gain deeper understanding of how models learn from data — one step closer to mastering AI!
