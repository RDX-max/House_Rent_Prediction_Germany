# House Rent Prediction Germany

**AIM**: to predict Total Rent  


**DATA**

1. data available from here: https://www.kaggle.com/datasets/corrieaar/apartment-rental-offers-in-germany

2. The data directory in this git has a smaller version of the dataset "subset_immo_data.csv" , showing what the data looks like.

3. Text data columns are 'desciption' and 'facilities' . These two were embedded using tinyBERT which is a smaller version of BERT and therefore computationally "cheaper" . A subset of this data is also given in the data directory showing what the columns look like after embedding. It is named embedded_data.csv 


**NOTEBOOK**

The notebook project.ipynb does all 3: 
1. Data cleaning
2. Training a model with only the structured data
3. Training a model with both structured and Text data

** There is a discussion section included at the end of the notebook containing the following**
1. Feature Processing and Model Selection: Provide a comprehensive discussion on how you processed the features, selected your model(s), and your rationale behind these choices.
2. Model Performance Analysis: Evaluate and compare the performance of the two models. Discuss any observable differences and potential reasons.
3. Improvement Strategies: Suggest ways the models could be improved or optimized.
