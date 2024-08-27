# House Rent Prediction Germany

**AIM**: to predict Total Rent  


**DATA**

data available from here: https://www.kaggle.com/datasets/corrieaar/apartment-rental-offers-in-germany

The data directory in my git has a smaller version of the dataset- "immo_data.csv" , to show you what the data looks like. 

Unstructured data comprises of 'desciption' and 'facilities' column. These two were embedded using tinyBERT which is a smaller version of BERT and therefore computationally "cheaper" . A subset of this data is also given in the data directory to show you what the data looks like. 


**NOTEBOOK**

The notebook data_processing.ipynb does all 3: 
1. Data cleaning
2. Training a model with only the structured data
3. Training a model with both structured and unstructured data




**TRAINED ML model**
Both trained ML models are found in the directory: model
Trained model with structured data: xgboost_step1.pkl
Trained model with unstructured data: xgboost_step2.pkl

