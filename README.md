
# Loan Approval Prediction System

This repository contains a machine learning-powered **Loan Approval Prediction System** developed using Python. The project uses a **Random Forest Classifier** to predict whether a loan application will be approved or rejected based on various input features. A user-friendly graphical interface is created with **Gradio** for easy interaction.

---

## Features

- **Machine Learning Models**:
  - Random Forest
  - Logistic Regression
  - Decision Tree
  - Support Vector Machine (SVC)

- **Data Analysis**:
  - Exploratory Data Analysis (EDA)
  - Data Preprocessing
  - Model Comparison based on Accuracy, Precision, Recall, and F1-Score

- **GUI for Predictions**:
  - User-friendly interface built with **Gradio**
  - Accepts user inputs for loan parameters and returns the loan approval status

---

## Dataset
The project uses a dataset containing various attributes related to individuals and their loan applications. The features include:
- Age
- Gender
- Education Level
- Income
- Employment Experience
- Home Ownership Status
- Loan Amount
- Loan Intent
- Interest Rate
- Credit History Length
- Credit Score
- Previous Loan Defaults

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/syedasharali/loan-approval-prediction-system.git
   cd loan-approval-prediction-system
   ```

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python loan_approval_project.py
   ```

---

## Usage

1. **Launch the GUI**:
   The Gradio-based interface will launch in your default browser. 

2. **Input Details**:
   Enter the required loan and user details (e.g., age, income, loan amount, etc.).

3. **Submit**:
   Click the **Submit** button to get an instant prediction of the loan status (Approved/Rejected).

---

## Project Structure

- `loan_approval_project.py`: The main Python script containing the data pipeline, machine learning models, and GUI implementation.
- `random_forest_model.pkl`: Pretrained Random Forest model.
- `requirements.txt`: List of required Python libraries.
- `README.md`: Project documentation (this file).

---

## Models Performance

| Model                 | Accuracy | Precision | Recall | F1-Score |
|-----------------------|----------|-----------|--------|----------|
| Random Forest         | 95%      | 94%       | 96%    | 95%      |
| Logistic Regression   | 89%      | 88%       | 89%    | 89%      |
| Decision Tree         | 91%      | 90%       | 92%    | 91%      |
| Support Vector Machine| 87%      | 85%       | 88%    | 86%      |

---


## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- Developed by **Syed Mohammad Ali Ashar**.
- Libraries used: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Gradio, Joblib.

---
