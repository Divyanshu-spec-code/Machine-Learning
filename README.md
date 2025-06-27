🪨 Sonar Rock vs Mine Prediction using Logistic Regression
This project uses a Logistic Regression model to classify sonar signals as either rock or mine based on the sonar dataset from the UCI Machine Learning Repository. The dataset contains 60 numerical features representing sonar signal strengths bounced off surfaces.

📌 Problem Statement
Sonar signals are used to detect objects under the sea. The goal is to predict whether the object is a rock or a mine (metal cylinder) based on the sonar return signal data.

📂 Dataset
Source: UCI Sonar Dataset

Features: 60 numeric attributes (energy values in different frequency bands)

Target:

R: Rock

M: Mine

⚙️ Technologies Used
Python 🐍

NumPy

Pandas

Matplotlib / Seaborn

Scikit-learn

📈 Model Used
Logistic Regression

Suitable for binary classification

Outputs probability and class label (0 or 1)

Used with scaling and train-test split

🚀 How to Run
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/sonar-rock-vs-mine.git
cd sonar-rock-vs-mine
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Code
bash
Copy
Edit
python sonar_logistic_regression.py
🧪 Project Workflow
Importing Libraries

Loading the Dataset

Data Exploration and Visualization

Data Preprocessing

Label encoding (R → 0, M → 1)

Train-test split

Feature scaling

Model Training

Logistic Regression with sklearn

Model Evaluation

Accuracy score

Confusion matrix

Classification report

Making Predictions

📊 Results
Accuracy: ~85%–90% (varies slightly due to train-test split randomness)

Model is able to distinguish between rock and mine objects effectively.

