Project Communuicate Data Findings
By Lokkan Cheng

I selected the Loan dataset from Prosper, which contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

The data dictionary docunment in this folder will also explain what are the variables in this data set.

This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.

Exploring the datset:

I looked up the dataset and would like to decided to know if there is any relationship between the loan status, employment status abd prosper rating. To check for this information, i plotted some plots to help me better understand their relationships.

My Findings:

Looking at the plots, the Loan status with "completed" is the lowest along the oter Loan status. And the loan status with "Current" is the highest. The employment Status "employed" its loan amount is the highest along with other employemnt status. The employed and the self employed have the same amount of active current loan.

The borrower whose income is higher have higher prosper rating. The borrower whose income is lower or not employed have lower prosper rating. One of the interesting thing that I found in this investigation is that the people who are non-employed have the lowest Prosper Rating while those borrowers who are employed have the highest Prosper Rating as well as the completed loan and the current loan. In 2013, there were more cancelled loan.


What do I need to install?

This project uses Python 3 and is designed to be completed through the Jupyter Notebooks IDE. It is highly recommended that you use the Anaconda distribution to install Python, since the distribution includes all necessary Python libraries as well as Jupyter Notebooks. The following libraries are expected to be used in this project:

NumPy
pandas
Matplotlib
Seaborn

Why this project?

Data visualization is an important skill that is used in many parts of the data analysis process. Exploratory data visualization generally occurs during and after the data wrangling process, and is the main method that you will use to understand the patterns and relationships present in your data. This understanding will help you approach any statistical analyses and will help you build conclusions and findings. This process might also illuminate additional data cleaning tasks to be performed. Explanatory data visualization techniques are used after generating your findings, and are used to help communicate your results to others. Understanding design considerations will make sure that your message is clear and effective. In addition to being a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.

What will I learn?

After completing this project, you will be able to:

Supplement statistics with visualizations to build understanding of data.
Choose appropriate plots, limits, transformations, and aesthetics to explore a dataset, allowing you to understand distributions of variables and relationships between features.
Use design principles to create effective visualizations for communicating findings to an audience.
