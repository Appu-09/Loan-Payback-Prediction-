📘 **Loan Payback Prediction using Deep Learning**

🧩 **Overview**

- This project was developed as part of the Kaggle Playground Series - Season 5, Episode 11 competition.
- The goal is to predict the probability that a borrower will pay back their loan using a synthetic dataset inspired by real-world financial data.

- By training and evaluating a deep learning model, this project aims to identify key borrower features that influence loan repayment probability , helping lenders make better, data-driven decisions.

🧠 **Objective**

- Predict the likelihood of a borrower repaying a loan (loan_paid_back).

- Evaluate performance using AUC (Area Under ROC Curve).

- Create a scalable and reproducible ML pipeline.

🗂️ **Dataset**

- The dataset comes from Kaggle:
🔗 Playground Series - S5E11: Predict Loan Payback

- To download it directly:

!kaggle competitions download -c playground-series-s5e11
unzip playground-series-s5e11.zip -d dataset


- The dataset includes:

- train.csv — borrower features + target variable (loan_paid_back)

- test.csv — borrower features for prediction

- sample_submission.csv — format for submission

⚙️ **Tech Stack & Libraries**

- Python 3

- Pandas / NumPy – data processing

- Scikit-Learn – feature scaling & preprocessing

- TensorFlow / Keras – deep learning model

- Matplotlib / Seaborn – visualization

🧮 **Model Workflow**

- Data Cleaning — filled missing values and encoded categorical columns.

- Feature Scaling — standardized numerical columns using StandardScaler.

- Model Building — trained a deep neural network (Dense layers with Dropout).

- Evaluation — measured model performance using ROC-AUC.

- Prediction — generated final probabilities for submission.

📈 **Results**

- The deep learning model achieved an AUC score of ~0.87 on validation data, demonstrating strong ability to differentiate between good and risky borrowers.
