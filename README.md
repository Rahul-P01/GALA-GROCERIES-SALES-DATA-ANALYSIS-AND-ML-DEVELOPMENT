
# GALA GROCERIES SALES DATA ANALYSIS AND ML DEVELOPMENT

## PROJECT DESCRIPTION
As a Data Scientist at Cognizant, I have been tasked to lead a team and analyse the multiple sales data of a client, Gala Groceries Limited. Gala Groceries is a new chain of grocery stores that have experienced magnficient growth within the last five (5) years in the United States.Their largest competitor is Wholefoods. <br />


They pride themselves on providing the best quality, fresh produce from locally sourced suppliers. However, this comes with many challenges to consistently deliver on this objective year-round.


Gala Groceries approached Cognizant to help them with a supply chain issue. Groceries are highly perishable items. If you overstock, you are wasting money on excessive storage and waste, but if you understock, then you risk losing customers. They want to know how to better stock the items that they sell. 


The Data Engineering team at Cognizant has extracted sample sales data across one week. My team has been tasked to provide recommendations as to what else is needed to fulfill the business requirement of Gala Groceries using this data.
Additionally, the team is to prepare and provide a python module that contains codes that perform machine learning modeling.


## PROJECT SUMMARY
| Code      | Name        |   Deployed App |
|-----------|-------------|:------|
|PP 2       | GALA GROCERIES SALES ANALYSIS  | |



## NOTES ON DATASETS


## TASKS
**TASK 1 : EXPLORATORY DATA ANALYSIS**
- Explore the client’s sales data as part of the Data Science team at Cognizant.
- Communicate findings and recommendations in an email to the Data Science team leader.
  
1.)	Sample_sales_data
https://cdn.theforage.com/vinternships/companyassets/e6nrxEAa6MHFh3Jmw/DCGoJxzfdJHirTYGe/1652216241761/sample_sales_data.csv

2.)	Eda_walkthrough
https://cdn.theforage.com/vinternships/companyassets/e6nrxEAa6MHFh3Jmw/DCGoJxzfdJHirTYGe/1652211590355/eda_walkthrough

3.)	Eda.ipynb
https://cdn.theforage.com/vinternships/companyassets/e6nrxEAa6MHFh3Jmw/DCGoJxzfdJHirTYGe/1652215992890/eda.ipynb

4.)	Getting started with colab
https://www.youtube.com/watch?v=i-HnvsehuSw

5.)	AI from data to Roi
 https://cdn.theforage.com/vinternships/companyassets/e6nrxEAa6MHFh3Jmw/DCGoJxzfdJHirTYGe/1652743458777/ai-from-data-to-roi.pdf
                        
6.)	How to upload a csv file into Google Colab
https://www.youtube.com/watch?v=woHxvbBLarQ
               
7.)	 Seaborn Documentation
https://seaborn.pydata.org/

8.)	 Matplotlib documentation 
https://matplotlib.org/


9.)	Pandas documentation
https://pandas.pydata.org/  

10.)	Email Template
https://medium.com/@rahulaipawar/how-to-write-an-e-mail-to-client-228d9623fae4

**TASK 2 : DATA MODELING**
- Review a data model diagram provided by the Data Engineering team and create a strategic plan as to how you’ll use this data to answer the problem statement.
- Summarize the choices and plan of work in a PowerPoint presentation.
  

**TASK 3 : MODEL BUILDING AND INTERPRETATION**
- Combine, transform and model the datasets in a suitable way to answer the problem statement that the business has requested.
- Communicate your work and analysis in the form of a PowerPoint slide to present the results back to the business.

**TASK 4 : MACHINE LEARNING PRODUCTION**
- Prepare a Python module that contains code to train a model and output the performance metrics for the Machine Learning engineering team.
- Additionally,develop an application using either Gradio, Streamlit or FastAPI to deploy and test the models.
### Machine Learning Algorithm Scores
| Models                                               | MAE   | 
| ---------------------------------------------------- |------ |
| SGD Linear Regression                                | 0.224 |

| Support Vector Machine                               | 0.226 |

| Random Forest                                        | 0.237 |

| Soft Voting Regressor (SGD LR, SVM)                  | 0.224 |

| Soft Voting Regressor (SGD LR, SVM, RF)              | 0.226 |

| SGD Linear Regression - Tuned                        | 0.223 |

| Support Vector Machine - Tuned                       | 0.223 |

| Soft Voting Regressor (SGD LR, SVM) - Tuned          | 0.223 |

## Code and Packages Used

Python version: 3.10.2
Packages: os, pandas, numpy, matplotlib, seaborn, sklearn, datetime, datetime_truncate, joblib


## SCREESHOTS OF DEPLOYED APP


# SETUP
It is recommended to have Virtual Studio Code or any other standard code editor on your local machine.<br />Install the required packages locally to your computer.

It is recommended that you run a python version 3.0 and above. 
You can download the required python version from [here](https://www.python.org/downloads/).

Use these recommended steps to set up your local machine for this project:

1. **Clone the repo :** To clone this repo, copy the url and paste it in your GitHub desktop or code editor on your local machine.
        
        https://github.com/Rahul-P01/GALA-GROCERIES-SALES-DATA-ANALYSIS-AND-ML-DEVELOPMENT.git

1. **Create the Python's virtual environment :** <br />This will isolate the required libraries of the project to avoid conflicts.<br />Choose any of the line of code that will work on your local machine.

            python3 -m venv venv
            python -m venv venv


2. **Activate the Python's virtual environment :**<br />This will ensure that the Python kernel & libraries will be those of the created isolated environment.

            - for windows : 
                         venv\Scripts\activate

            - for Linux & MacOS :
                         source venv/bin/activate


3. **Upgrade Pip :**<br />Pip is the installed libraries/packages manager. Upgrading Pip will give an to up-to-date version that will work correctly.

            python -m pip install --upgrade pip


4. **Install the required libraries/packages :**<br />There are libraries and packages that are required for this project. These libraries and packages are listed in the `requirements.txt` file.<br />The text file will allow you to import these libraries and packages into the python's scripts and notebooks without any issue.

            python -m pip install -r requirements.txt 

# MACHINE LEARNING MODEL DEPLOYMENT
## Run Streamlit App
A streamlit app was added for further exploration of the model. The streamlit app provides a simple Graphic User Interface where predicitons can be made from inputs.

- Run the demo app (being at the root of the repository):
        
        Streamlit run streamlit.app.py
## Figures

### Unit Price Distribution
![Unit Price Distribution](Figures/unit_price_distribution.png)

### Sales Total Distribution
![Sales Total Distribution](Figures/sales_total_distribution.png)

### Sales By Category
![Sales By Category](Figures/categories_by_sales.png)


# EVALUATION


# RESOURCES


## CONTRIBUTORS

| NAME    :- Rahul Pawar|

| E-MAIL  :- rahulaipawar@gmail.com | 

| Linkedin:- www.linkedin.com/in/rahul-ai-pawar|

| Medium  :- https://medium.com/@rahulaipawar |

| Phone   :- +91 9098879776 |





