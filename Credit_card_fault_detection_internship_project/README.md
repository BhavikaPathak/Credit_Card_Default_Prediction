# Credit Card Default Prediction End to End Deployment

Financial threats are displaying a trend about the credit risk of commercial banks as the
incredible improvement in the financial industry has arisen. In this way, one of the
biggest threats faces by commercial banks is the risk prediction of credit clients. The
goal is to predict the probability of credit default based on credit card owner's
characteristics and payment history.

## Website Link (Credit Card Default Prediction)

https://creditcarddefaultprediction.netlify.app

## Technical aspect
Python 3.7
Front-end: HTML, CSS, Bootstrap
Back-end: Flask framework
IDE: Jupyter Notebook, PyCharm
Database: MongoDB Atlas
Deployment: Netlify

# How to run this app?

Code is written in Python 3.7. If you don't have python installed on your system, click here https://www.python.org/downloads/ to install.

- Create virtual environment: conda create -n myenv python=3.7
- Activate the environment: conda activate myenv
- Install the packages: pip install -r requirements.txt
- Run the app: python app.py

# Data Collection

The dataset is collected from Kaggle.

# Model Creation and Evaluation

- Various classification algorithms like Logistic Regression, Random Forest, Decision Tree, Naïve Bayes, Support Vector Machine tested.
- Random Forest, Decision Tree and Logistic regression were given better results. Random Forest was chosen for the final model training and testing.
- Model performance evaluated based on accuracy, confusion matrix, classification report.

# Database Connection

MongoDB Atlas database used for this project

# Model Deployment

The final model is deployed on Netlify using Flask framework .
