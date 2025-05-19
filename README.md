![Banner image stating 'Credit Card Churn Analysis'](image-1.png)

This is a short project looking at credit card attrition rates using an ETL(Extract, Transform, Load) pipeline and some visualisations. Churning according to [Forbes](https://www.forbes.com/advisor/credit-cards/what-is-credit-card-churning/) is the process in which customers switch between banks to get sign up perks for this analysis we will be looking at general attrition rates. Attrition does not necessarily mean all those who leave are engaging in churning but it can still form the basis for further inquiry. 
## Navigation:
* [Data Investigations Notebook](https://github.com/Janeweightman/Credit-card-churn-analysis/blob/main/jupyter_notebooks/Datainvestigations.ipynb)
* [Visualisations Notebook](https://github.com/Janeweightman/Credit-card-churn-analysis/blob/main/jupyter_notebooks/Visualisations.ipynb)
* [Raw Data](https://github.com/Janeweightman/Credit-card-churn-analysis/blob/main/data/BankChurners.csv)
* [Cleaned Data](https://github.com/Janeweightman/Credit-card-churn-analysis/blob/main/data/cleaned.csv)

# *Dataset Content*
Data comes from this [kaggle dataset.](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)
# *Business Requirements*
Banks wish to retain customers and a high attrition rate means less profit.
If we can identify the trends in attrited customers we can potentially lower attrition rates by either changing how the bank operates or by changing the demographics we market to. 
# *Hypotheses*
## Hypothesis 1: 
Younger people are more likely to take risks with their credit score and will be more likely to engage in risky behaviour such as frequent churning. This will be tested by plotting a histogram that examines the distribution of attrition rates across age ranges. 
### Result: 
Age doesn’t seem to have relationship with attrition
## Hypothesis 2: 
Men are more likely to engage in churning than women. This will be tested with a stacked bar graph plotting attrited and current customers by gender. 
### Result: 
Women seemed marginally more likely to be attrited customers than men but not to a significant degree.
## Hypothesis 3:  
Attrited Customers will be on the books for less time than the current customers. This will be tested via a scatter plot looking at the distribution of attrited customers and their months on the books.
### Result: 
The months on the books were evenly distributed among both current customers and attrited customers.
## Hypothesis 4: 
 Attrited Customers will have lower total transaction amounts than current customers. This is because transactors with regards to credit cards are those that pay off their full bill on time every month according to [Investopedia](https://www.investopedia.com/terms/t/transactor.asp) and I believe that those who don't pay their bills on time are more likely to stop using their credit card. This will be tested using a scatter plot and the distribution of attrited customers and their transaction amounts.
### Result: 
Those with low transaction amounts are ideed more likely to be attrited.


# The rationale to map the business requirements to the Data Visualisations
* The **first visualisation** is a pie chart illustrating the attrition rates, this helps identify the scale of the problem. This allows the business to see whether it is worth investing resources into tackling the problem.
* The **second visualisation** is a histogram that plots the age distribution with attrition rates. This allows the bank to see whether it is worth targeting different age demographics more with marketing.
* The **third visualisation** is a stacked bar chart that plots attrition rates for gender. This allows the bank to potentially determine whether they should pivot their marketing more towards men or women.
* The **fourth visualisation** is a scatter plot that visualizes attrition rates and gender with months on the books and total transaction amounts. This type of visualisation has a number of potential business implications for example months on the books with attrition rates could determine perks they give to long term customers and the same could be shown for high transaction amounts.
# Analysis techniques used
* *Extract Transform load pipeline with data cleaning in Jupyter notebooks.*
* *Visualisations: pie chart, histogram, bar chart and scatter plot.*
# Ethical considerations
Financial data is highly sensitive and requires compliance to GDPR and other regulations, in order to protect sensitive infomation I have anonymised the data by removing client numbers.

# Technologies used
* Visual Studio Code
* Python 
* Jupyter notebook
* Microsoft Co-Pilot 

# Planning
* I used github project board to help me plan and keep track of my progress.

# Development Roadmap
A struggle I encountered was getting Plotly graphs to work due to NBFormat issues, this was solved using Microsoft co-pilot that required a pip update. 
# Data Analysis Libraries
Pandas, Numpy, Plotly, Seabon and Matplotlib.
# Credits
* The Code Institute Learning Management System modules on pandas and data visualisations with Matplotlib,Seaborn and Plotly.
* Microsoft Copilot integrated into VS code was used to help with code generation and debugging.
* Users Daniel and Alvaro Fuentes on [Stack Overflow](https://stackoverflow.com/questions/21572870/percent-label-position-in-pie-chart) regarding percentage markers in Matplotlib pie charts 
* [Markdown guide](https://www.markdownguide.org/cheat-sheet/) was used to format the README.md and markdown cells in the Jupyter notebooks.
# Media
Header image for this document was made using [Canva.](https://www.canva.com/)
# Acknowledgements 
Special thanks to my tutors Emma Lamont, Mark Briscoe, John Rearden and Niel McEwan from the Code Institute for all their help on the course!
