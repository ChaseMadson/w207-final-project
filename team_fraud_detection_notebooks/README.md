# Final Project - Detecting Fraudulent Credit Card Transactions

| Course | Term | Section | Group | Objective | Kaggle URL |
| --- | --- | --- | --- | --- | --- |
| W207 | Fall 2022 | 11 | 2 | Detect fraudulent credit card transactions | IEEE-CIS Fraud Detection ([Link](kaggle.com/competitions/ieee-fraud-detection)) |

**Group Members**
- Naikaj Pandya
- Chase Madson
- Eric Danforth

# Notebooks in this Folder

* **1_main_neural_network_model.ipynb**: The notebook containing the end-to-end solution of the main neural network model using the Keras Sequential API.  

* **2_latest_transaction_by_card_model.ipynb**: A branch of the main_neural_network_model.ipynb developed to emulate the data generating process for our labels. Includes code to ensemble (i.e., simple average) its predictions with the predictions from main_neural_network_model.ipynb, which yields this team's greatest Kaggle score. 

* **3_functional_model.ipynb**: A separate end-to-end solution of the neural network model using the Keras Functional API. 
This notebook also includes some additional EDA. 

* **4_tpu_model.ipynb**: An additional branch of the main_neural_network_model.ipynb model developed to experiment running end-to-end solution on TPUs over Google Colab. 
