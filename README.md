# Student Exam Score prediction (Linear Regression )
 A beginner-friendly machine learning project that predicts a student’s exam score based on the number of hours studied.
This project also includes helpful visualizations such as a scatter plot and a histogram to understand the dataset better.


---

📌 Project Overview

This project analyzes how the number of hours a student studies affects their exam performance.
We explore the dataset, visualize it, and build a Linear Regression model to find the relationship between study hours and exam scores.

The project includes:

Data visualization (scatter plot + histogram)

Linear regression model

Prediction function

Error evaluation metrics

Clean, beginner-friendly code



---

🧠 What You Will Learn

Loading and exploring data with Pandas

Visualizing data using Scatter Plot and Histogram

Understanding relationships between variables

Training a regression model with Scikit-Learn

Evaluating model accuracy using MAE, MSE, RMSE, R²



---

📊 Visualizations Used

1️⃣ Scatter Plot

Shows the relationship between hours studied (x-axis) and exam scores (y-axis).
This helps understand how scores increase with study time.

2️⃣ Histogram

Shows the distribution of exam scores and helps identify score ranges where most students fall.

These visualizations make the dataset easier to understand before training the model.


---

📂 Project Structure

student-score-prediction/
│── data/
│   └── student_exam_scores.csv
│
│── notebook/
│   └── Student_Score_Prediction.ipynb
│
│── README.md
│── requirements.txt


---

🔧 Technologies Used

Python

Pandas

Matplotlib

Scikit-Learn

Jupyter Notebook / Google Colab



---

🚀 Model Used

Linear Regression

The model fits a straight line of best fit:

\text{Predicted Score} = m \times \text{Hours Studied} + b

It learns the values of m and b from the data.


---

📉 Model Performance (Example)

Metric	Value (approx)

MAE	3–5
MSE	~18
RMSE	~4.27
R²	~0.96



---

🧪 Example Prediction

If a student studies 8 hours, predicted score may be:

Predicted score: ~79


---

▶️ How to Run

1. Clone this repository

git clone https://github.com/your-username/student-score-prediction.git
cd student-score-prediction

2. Install dependencies

pip install -r requirements.txt

3. Open the Jupyter Notebook

jupyter notebook


---

⭐ Future Enhancements

Add more variables (sleep, assignments, past performance)

Try non-linear models

Build a small web app with Streamlit



---
