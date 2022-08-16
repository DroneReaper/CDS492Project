# CDS492Project
CDS 492 Project Code
This project revolves around finding number of monthly delays caused by specific airlines. Data is collected from the Bureau of Transportation Statistics and compiled into a new dataset found in this repository. Data used includes delay data, employee data, and passenger data from 2015-2021 for select airlines. This project contains baseline regression models that find the most important outputs for regression models which are R2 score, mean squared error, mean absolute error, and root mean squared error. These baseline models is used with their keras model counterpart to determine the performance of the keras model in determining monthly carrier relate delays. The variables used to determine this are total employees and total passengers. All code is in python and stored in Jupyter Notebook files.

There is an exploratory analysis file that goes through visualizations of the data in detail to better show correlation between data before being used within the regression models. Another file is present which is dedicated to all the linear regressions that were conducted on the data. A third file is also present which is the code for all the keras models used.

The shortcoming of the models provided are the explanatory variables used. To improve upon the model more variables that relate to carrier specific delays with higher correlation to delay rates could be implemented to create a more accurate prediction model. An expanded dataset that spans more than the years given which are 2015-2021 could also help improve the model.

Source Datasets:

Delays: https://www.transtats.bts.gov/ot_delay/OT_DelayCause1.asp?20=E
Employee: https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=GEF&QO_fu146_anzr=
Passenger: https://www.transtats.bts.gov/Data_Elements.aspx?Data=5
