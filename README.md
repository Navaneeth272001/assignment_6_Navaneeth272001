# Name: Navaneethakrishnan V
# Roll Number: DA24S008

## Assignment Overview:
Missing data is a common challenge in real-world datasets. How we handle these missing values can significantly influence the performance of machine learning models. In the code, different Missing At Random (MAR) scenarios are simulated, and four distinct strategies for handling missingness are compared.

### Dataset
- Source: UCI Machine Learning Repository — Default of Credit Card Clients Dataset
- Target Variable: default.payment.next.month (1 = default, 0 = no default)
- Key Features Used for Missingness Simulation
    - AGE
    - BILL_AMT1 (bill amount in September 2005)
    - PAY_AMT3 (payment amount in July 2005)

### Install Dependencies:
pip install pandas numpy scikit-learn seaborn matplotlib

assignment_6_Navaneeth272001/
│
├── UCI_Credit_Card.csv              # Dataset
├── credit_default_missing_data.ipynb  # Main Jupyter Notebook
├── README.md                        # Project summary (this file)
└── plots/
    └── f1_score_comparison.png      # Visualization of model performance

