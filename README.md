![Illustration of credit risks](https://user-images.githubusercontent.com/67468718/149666189-fbae54b6-b123-4905-8348-e59ec94cdb1c.png)
# Credit-Risk-Classification
In this project, I use various techniques to train and evaluate a model based on loan risk. Specifically, a dataset of historical lending activity from a peer-to-peer lending services company will be used to build a model that can identify the creditworthiness of borrowers.

## Usage
To see the code for the credit risk classification model, please navigate to "credit_risk_classification.ipynb". The original dataset that I used to train the model is located in the "Resources" folder, under the "lending_data.csv" name. I've also written an analysis report, delineating the precision, recall and accuracy scores that the model achieved and whether this model should be used for the purpose of 
classifying high-risk loans. Please navigate to "report-template.md" to see my analysis. 

## Installations
The following dependencies were used to run the code. Please copy the code to your code editor as is:
1. `import numpy as np`
2. `import pandas as pd`
3. `from pathlib import Path`
4. `from sklearn.metrics import confusion_matrix, classification_report`

Please ensure you have the following libraries pre-installed:
1. Pandas: `pip install pandas`
2. Scikit-learn: `pip install scikit-learn`
3. Numpy: `pip install numpy`

## Building our classification model
### Our dataset
Our current dataset contains the following columns:
1. `loan_size`	
2. `interest_rate`	
3. `borrower_income`
4. `debt_to_income`	
5. `num_of_accounts`	
6. `derogatory_marks`	
7. `total_debt`	
8. `loan_status`

Note that the target is the `loan_status` column while the rest contribute to the features of our model.

![Alt text](<Screenshot 2023-12-17 at 11.09.07 pm.png>)

### Model's performance
After the model had been built, I generated a classification report to evaluate our model. The results are summarised in the table below:

![Alt text](<Screenshot 2023-12-17 at 11.11.24 pm.png>)

## Contributions
Special thanks to the following people for their contribution to the project:\
-Jefferey Chieh-Liu\
-Mortaza Rezae\
-BCS assistants