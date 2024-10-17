# Online_Payment_Fraud_Detection_ML
Overview:
This project aims to develop a machine learning-based system to detect online payment fraud. The system utilizes various ML algorithms to identify suspicious transactions and prevent financial losses.

Dataset:

- Source: Kaggle
- Description: Contains features extracted from online transactions, including:
   step: represents a unit of time where 1 step equals 1 hour
   type: type of online transaction
   amount: the amount of the transaction
   nameOrig: customer starting the transaction
   oldbalanceOrg: balance before the transaction
   newbalanceOrig: balance after the transaction
   nameDest: recipient of the transaction
   oldbalanceDest: initial balance of recipient before the transaction
   newbalanceDest: the new balance of recipient after the transaction
   isFraud: fraud transaction
- Target Variable: isFraud (1) or Legitimate (0)

  Methodology:

1. Data Preprocessing:
    - Handling missing values
    - Feature scaling
    - Data normalization
2. Feature Engineering:
    - Extracting relevant features from transaction data
    - Creating new features using domain knowledge
  
  Requirements:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- TensorFlow (for Neural Network)
- Matplotlib/Seaborn (for visualization)
