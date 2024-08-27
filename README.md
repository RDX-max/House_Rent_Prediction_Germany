# House Rent Prediction Germany

**AIM**: to predict Total Rent  


**DATA**

data available from here: https://www.kaggle.com/datasets/corrieaar/apartment-rental-offers-in-germany

The data directory in my git has a smaller version of the dataset- "subset_immo_data.csv" , to show you what the data looks like. 

Unstructured data comprises of 'desciption' and 'facilities' column. These two were embedded using tinyBERT which is a smaller version of BERT and therefore computationally "cheaper" . A subset of this data is also given in the data directory to show you what the data looks like. It is named embedded_data.csv 


**NOTEBOOK**

The notebook data_processing.ipynb does all 3: 
1. Data cleaning
2. Training a model with only the structured data
3. Training a model with both structured and unstructured data

   There is a discussion section included at the end of the notebook




**TRAINED ML model**


Both trained ML models can be downloaded from here

Trained model with structured data can be downloaded from here : https://drive.google.com/file/d/11M_blGluyCYekYljvy9v_z0tBVlQtkHe/view?usp=sharing 

Trained model with unstructured data can be downloaded from here: https://drive.google.com/file/d/1-Hltz3PwJ5Hz0LCTSE6pWGx9kJLp55HP/view?usp=sharing

