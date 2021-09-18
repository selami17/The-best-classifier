# The-best-classifier

In this notebook I have tried to use all the classification algorithms that I have learned in Machine Learning with Python course authorized by IBM.

Lets first load required libraries:

In [1]: import itertools import numpy as np import matplotlib.pyplot as plt from matplotlib.ticker import NullFormatter import pandas as pd import numpy as np import matplotlib.ticker as ticker from sklearn import preprocessing %matplotlib inline About dataset This dataset is about past loans. The Loan_train.csv data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

Field Description Loanstatus Whether a loan is paid off on in collection Principal Basic principal loan amount at the Terms Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule Effectivedate When the loan got originated and took effects Due_date Since it’s one-time payoff schedule, each loan has one single due date Age Age of applicant Education Education of applicant Gender The gender of applicant Lets download the dataset

