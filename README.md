# Customer Churn Prediction

## Overview
This project predicts whether a telecom customer will churn (leave) using machine learning. 
A binary classification problem using real customer data from IBM Telco dataset.

## Problem Statement
Telecom companies lose customers every month. By predicting who is likely to churn, 
they can take proactive retention measures.

## Dataset
- **Source:** IBM Telco Customer Churn Dataset (Kaggle)
- **Samples:** 7,043 customers
- **Features:** 21 (demographics, services, account info)
- **Target:** Churn (Yes/No)

## Project Structure 
customer-churn-prediction/

├── README.md

├── requirements.txt

├── .gitignore

├── data/

│   └── (will add dataset here)

├── notebooks/

│   └── churn_prediction.ipynb

└── src/

├── preprocessing.py

├── model.py

└── evaluation.py

## Technologies Used
- **Python 3.8+**
- **pandas** - Data manipulation
- **scikit-learn** - Machine learning models
- **matplotlib/seaborn** - Visualization
- **numpy** - Numerical computing

## How to Run

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/customer-churn-prediction.git
cd customer-churn-prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Download dataset
- Go to [Kaggle Telco Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Download `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- Place it in the `data/` folder

### 4. Run the notebook
```bash
jupyter notebook notebooks/churn_prediction.ipynb
```

## Model Performance
(Will update after training)
- Accuracy: 
- Precision: 
- Recall: 
- F1-Score: 

## Key Features
(Will identify after feature importance analysis)

## Next Steps
- Hyperparameter tuning
- Deploy with Flask/FastAPI
- AWS deployment

## Author
Urvija Palaskar

## License
MIT


