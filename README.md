![Banner showing credit card analysis with charts and graphs, featuring a credit card and financial icons on a blue background. The image conveys a professional and analytical tone. Text in the image reads Credit Card Churn Analysis.](../image/credicardchurnanalysisimage.png)

This is a short project looking at credit card attrition rates using an ETL(Extract, Transform, Load) pipeline and some visualisations. Churning is the process in which customers switch between banks to get sign up perks(https://www.forbes.com/advisor/credit-cards/what-is-credit-card-churning/) for this analysis we will be looking at general attrition rates. Attrition does not necessarily mean all those who leave are engaging in churning but it can still form the basis for further inquiry. 
# *Dataset Content*
Data comes from this kaggle dataset  https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers 
# *Business Requirements*
Banks wish to retain customers and a high attrition rate means less profit.
If we can identify the trends in attrited customers we can potentially lower attrition rates by either changing how the bank operates or by changing the demographics we market to. 
# *Hypotheses*
Hypothesis 1: Younger people are more likely to take risks with their credit score and will be more likely to engage in risky behaviour such as frequent churning. This will be tested by plotting a histogram that examines the distribution of attrition rates across age ranges. 
Result: Age doesn’t seem to have relationship with attrition
Hypothesis 2: Men are more likely to engage in churning than women. This will be tested with a stacked bar graph plotting attrited and current customers by gender. 
Result: Women seemed marginally more likely to be attrited customers than men but not to a significant degree.
Hypothesis 3:  Attrited Customers will be on the books for less time than the current customers. This will be tested via a scatter plot looking at the distribution of 
Result: The months on the books were evenly distributed among both current customers and attrited customers.
Hypothesis 4:  Attrited Customers will have lower total transaction amounts than current customers. This will be 


The rationale to map the business requirements to the Data Visualisations
The first visualisation is a pie chart illustrating the attrition rates, this helps identify the scale of the problem. This allows the business to see whether it is worth investing resources into tackling the problem. 
The second visualisation is a histogram that plots the age distribution with attrition rates. This allows the bank to see whether it is worth targeting different age demographics more with marketing. 
The third visualisation is a stacked bar chart that plots attrition rates for gender. This allows the bank to potentially determine whether they should pivot their marketing more towards men or women. 
The fourth visualisation is a scatter plot that visualizes attrition rates and gender with months on the books and total transaction amounts. This type of visualisation has a number of potential business implications for example months on the books with attrition rates could determine perks they give to long term customers and the same could be shown for high transaction amounts. 
Analysis techniques used
Extract Transform load pipeline with data cleaning in Jupyter notebooks
Visualisations: pie chart, histogram, bar chart and scatter plot. 
Ethical considerations
Financial data is highly sensitive and requires compliance to GDPR and other regulations, however this is just a simple analysis using synthetic freely available data on kaggle so does not have such considerations. 


Development Roadmap
A struggle I encountered was getting Plotly graphs to work due to NBFormat issues, this was solved using Microsoft co-pilot that required a pip update. 
 Data Analysis Libraries
Pandas, Numpy, Plotly, Seabon and Matplotlib
Credits
The Code Institute Learning Management System modules on pandas and data visualisations with Matplotlib,Seaborn and Plotly 
Microsoft Copilot integrated into VS code.
Techniques taught directly from John Rearden from Code institute 
Users Daniel and Alvaro Fuentes on Stack Overflow regarding percentage markers in Matplotlib pie charts https://stackoverflow.com/questions/21572870/percent-label-position-in-pie-chart 
Media
Header image for this document was made using Canva
Acknowledgements 
Special thanks to my tutors Emma, Mark, John and Niel from the Code Institute!
