# Bank-Note-Authentication-using-FastAPI

#### This is a simple BankNote Authentication system built using Machine Learning.
#### A Random Forest Classifier is trained on banknote measurement data to predict whether a banknote is real or fake.
#### The model is deployed using FastAPI.

## Files in this Project :

### ├── app.py                    

### ├── banknote.py                  

### ├── BankNote_Authentication.csv        

### ├── classifier.pkl                

### ├── Model_training.ipynb         

### ├── requirements.txt              


## Banknote Features Used :

- ### Variance
- ### Skewness
- ### Curtosis
- ### Entropy

## Technologies Used :

- ### Python
- ### FastAPI
- ### Scikit-learn
- ### Pandas
- ### Numpy

## How to Run :

- ## Install dependencies:  pip install -r requirements.txt

- ## Run the app:  uvicorn app:app --reload

- ## Open your browser and go to:  http://127.0.0.1:8000/docs

## Model :
- ### Algorithm: Random Forest Classifier
- ### Output: 0 = Genuine, 1 = Fake
