# Predicting Academic Success

This repo includes some documentation of the group project Predicting Academic Success of NY Public Schools, which was prepared as part of the 2023 Data BootCamp. Predicting Academic Success of New York Public Schools project explores the predictors of graduation rate in New York public schools at elementary and high school levels. The project uses linear regression and classification.

# Key Question
Using school-level features, can we accurately predict school-level academic success for New York public (including charter) schools? 

In addition to informing parents, this information is critical to informing state and local leaders who attempt to improve public schools through policy creation and implementation.

# Data and Cleaning
We downloaded our data from [NY State Data](https://data.nysed.gov/downloads.php). This database comes in Microsoft Access Format and has over twenty different datasets. After exploring different spreadsheets, we decided to work with the following eight files: 

* The ``Expenditures Per Pupil.xlsx`` data consists of per pupil yearly spending for each school.
* The ``Inexperienced Teachers and Principals.xlsx`` data consists of the percentage of teachers teaching with less than four years of experience. 
* The ``Teachers Teaching Out of Certification.xlsx`` data consists of the percentage of teachers at the school who are not certified in the subject or grade they teach.
* The ``ACC EM Chronic Absenteeism.xlsx`` data consists of the percentage of students at the elementary school who were absent for more than 10% of total school days.
* The ``ACC HS Chronic Absenteeism.xlsx`` data consists of the percentage of students at the high school who were absent for more than 10% of total school days.
* The ``ACC EM Core and Weighted Performance.xlsx`` data consists of a composite score determined from elementary English language arts, mathematics, and science assessment scores.
* The ``ACC HS Core and Weighted Performance.xlsx`` data consists of a composite score determined from secondary English language arts, mathematics, science, and social studies Regents exams scores.

# Exploratory Data Analysis
See ``ExploratoryDataAnalysis.ipynb`` in the ``./EDA`` folder for some Jupyter notebooks examining the data. We plotted scatter plots for our features, which are all continuous variables.

# Modeling
Using these data, we developed linear and non-linear models. See ``./Modelling`` for more information and corresponding notebooks of our models and model comparison.



 



