# 🧠 Insurance Premium Prediction Model
This project uses a dense neural networkmodel built with TensorFlow/Keras to predict insurance premiums based on user features such as age, BMI, smoking status, etc. The goal is to provide a quick and interpretable solution to estimate insurance charges.

## 📊 Dataset
The model uses the popular Medical Cost Personal Dataset, which includes:
1) age: Age of the individual
2) sex: Sex of the individual (female, male)
3) bmi: The person's Body mass index
4) children: Number of children covered by health insurance
5) smoker: Whether they smoke or not
6) region: Residential area in the US
7) charges: Medical insurance cost (target variable)

## 🔧 Technologies Used
1) Program written using Python
2) Pandas & NumPy (Data manipulation)
3) Scikit-learn (Preprocessing & evaluation)
4) TensorFlow / Keras (Model building)
5) Matplotlib & Seaborn (Visualization)

## 📈 Model Overview
Type: Deep Neural Network
Input: Normalized numerical and encoded categorical features
Output: Predicted insurance charges (continuous value)
Loss Function: Mean Squared Error (MSE)
Metrics: Mean Absolute Error (MAE)

## 📉 Performance
- Training MAE: ~2 500
- Validation MAE: ~2 500
- Testing MAE: ~2 500

🧮 Real-World Use Cases
1) Use Case #1: Individuals estimating insurance costs.
   A person could use this model to estimate how much they might be quoted for a health insurance plan, given their personal details. It helps consumers understand which factors most impact their      premiums.

3) Use Case #2: Insurance companies pricing plans.
   Insurers can use this model (or more advanced versions) to automatically generate premium quotes for new applicants, based on risk factors.
   It’s essentially a pricing tool that helps predict what to charge a person and create more optimized pricing plans.
