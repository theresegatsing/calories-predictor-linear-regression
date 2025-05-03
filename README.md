# 🔥 Calories Predictor - Linear Regression

A Python project that implements **linear regression from scratch** (without using libraries like `scikit-learn`) to **predict calories burned** based on key physical activity features. The model is trained using **gradient descent** and tested on unseen data for realistic predictions.

---

## 🔍 Features Used

- Distance covered  
- Speed  
- Age  
- Weight  

---

## ✅ Highlights

- Implemented core Machine Learning concepts **manually using NumPy**  
- **Visualized** the cost function over iterations  
- Made **predictions** using new/unseen data  

---

## 📦 Technologies

- Python  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## 📊 Example Prediction

```python
input = np.array([4.2, 6.5, 21, 58])  # distance, speed, age, weight
calories = compute_calories(input, final_w, final_b)
print(f"Predicted calories burned: {calories:.2f}")
