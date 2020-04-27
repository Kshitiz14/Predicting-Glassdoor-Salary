# Predicting-Data Scientist-Salary
Creating a model to predict the salary of a data scientist based on the job description found on Glassdoor website.

Python version: 3.7.0

Python Packages: pandas, numpy, matplotlib, seaborn, sklearn

# Data Collection
Data can be collected from various sources. One of the most popular form of data is in CSV format but it is essential to know that most of the time data are not in CSV form. Beside CSV, data can be extracted from text file, pdf file or through API or web scrapping. 

# Data Cleaning
Data cleaning is the most important step in the data analysis process. Most of the time, data are in raw format. If not cleaned appropriately, our predictive model will not provide accurate and concise output. In data analysis, Garbage in is Garbage Out. So, it was important to perform data cleaning in our glassdoor data. 

In our data, we will change the elements of dataframe into more readable format such as changing the salary estimate from $81k - $100K to 81 - 100. We have also derived new columns from the existing column which we believe will help us in making better prediction. For example, we created column with average salary, we created new columns containing how many times job description required knowledge of python, R, spark, etc. 

# Exploratory Data Analysis
Next step is to explore the data through visualization. We should always perform exploratory data analysis before moving to model building. EDA not only help us to summarize the main characteristics but also provides intuition for our statistical model. EDA is a simple way to find any discrepancy in our data through visualization. 

Some of the visualization from our EDA are
![Histogram](https://github.com/Kshitiz14/Predicting-Glassdoor-Salary/blob/master/1.PNG)
![Wordcloud](https://github.com/Kshitiz14/Predicting-Glassdoor-Salary/blob/master/2.PNG)

# Model Building
Now we are finally building our prediction model.There are various prediction algorithm such as regression, classification, clustering, etc. Based on the nature and characteristics of the data, needed outcome, we can choose our algorithm. Since, we are predicting quantitative amount, regression would be best choice. Even in regression we would use three model multiple linear regression, lasso regression and random forest. Among three model, we chose the random forest since it performed the best. 
