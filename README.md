🏠 House Rent Prediction Using Linear Regression
📌 Project Overview

This project implements a Linear Regression Model to predict house rent based on:

📐 Size (Square Feet)

🛏 BHK (Bedrooms, Hall, Kitchen)

🚿 Number of Bathrooms

The model is trained using supervised machine learning.

🎯 Objective

To build a Multiple Linear Regression model that predicts rent using:

𝑅
𝑒
𝑛
𝑡
=
𝑏
0
+
𝑏
1
(
𝑆
𝑖
𝑧
𝑒
)
+
𝑏
2
(
𝐵
𝐻
𝐾
)
+
𝑏
3
(
𝐵
𝑎
𝑡
ℎ
𝑟
𝑜
𝑜
𝑚
)
Rent=b0+b1(Size)+b2(BHK)+b3(Bathroom)
🛠 Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

📂 Dataset Features
Feature	Description
Size	Area in square feet
BHK	Number of Bedrooms
Bathroom	Number of Bathrooms
Rent	Target variable
🚀 Installation

Install required libraries:

pip install pandas numpy scikit-learn matplotlib
▶ How to Run

Open Jupyter Notebook / VS Code

Run the Python script

Train the model

Predict rent for new house data

Example prediction:

model.predict([[1600, 3, 2]])
📊 Model Evaluation

Mean Squared Error (MSE)

R² Score

Higher R² value indicates better performance.

📈 Output Example
Predicted Rent: 21000
📌 Project Structure
├── house_rent.py
├── rent_model.pkl
└── README.md
👩‍💻 Author

Your Name

If you want, I can also give:

🔥 Professional GitHub README version

📊 Add screenshots section

📄 Mini project report format

🧠 Viva questions & answers
