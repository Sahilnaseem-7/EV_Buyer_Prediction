EV Buyer Prediction

A machine learning project to predict the probability of a customer purchasing an electric vehicle using Random Forest Classification.

📌 Project Overview

The goal of this project is to predict whether a customer is likely to buy an electric vehicle based on various customer and EV-related features.

The model is evaluated using ROC-AUC, which measures how well the model distinguishes between potential EV buyers and non-buyers.

🔍 Workflow
Data exploration and understanding
Missing-value and duplicate checks
Target variable analysis
Removal of the id column
Identification of numerical and categorical features
One-hot encoding of categorical features
Stratified train-validation split
Random Forest classification
5-fold cross-validation
Generation of test-set purchase probabilities
Kaggle submission
🤖 Model

Random Forest Classifier

Number of trees: 300
Random state: 42
Evaluation metric: ROC-AUC
📊 Results
Evaluation	ROC-AUC
Validation Set	0.93526
5-Fold Cross-Validation	0.93532 ± 0.00073

The low standard deviation indicates consistent performance across the five validation folds.

🛠️ Technologies
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook
📁 Project Structure
EV-Buyer-Prediction/
│
├── README.md
├── ev_prediction.ipynb
├── submission.csv
└── requirements.txt

📈 Key Result

The Random Forest model achieved a 0.93532 mean ROC-AUC across 5-fold stratified cross-validation.

👤 Author

Sahil Naseem
