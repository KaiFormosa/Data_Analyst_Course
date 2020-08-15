# Data Analyst Program

This repository is a project portfolio for the "Data Analyst" certification program by Udacity. This program prepares students for a career as a data analyst by helping them learn to organize data, uncover patterns and insights, draw meaningful conclusions and clearly communicate critical findings. Each project is associated with an important subject of data analysis, where students are required to work with a coach at Udacity to demonstrate the skills learned.

These projects are not only designed to enhance the understanding of program material, but also provide a hands-on experience for students to develop proficiency in Python and its data analysis libraries (NumPy, Pandas, Matplotlib) and SQL. To complete the program, all project must be reviewed and approved by the coach.

Each folder in this repository is a collection of the working and data files for a project. The name of the folder starts with a subject of data analysis instructed in the program, followed by the title of the project associated with that subject. The coach's review of the project is saved as "Project_Review_by_Coach" in PDF format.

---

## Section 1: Introduction to Data Analysis

Skills/knowledge learned:
- Using Anaconda to manage packages and environments for use with Python
- Using Jupyter Notebook to combine explanatory text, math equations, codes and visualizations in one sharable document
- Steps in a data analysis process
- Wrangling the data into a desired format for analysis
- Investigating datasets with vectorized operations in NumPy and Pandas
- Communicating the results of the analysis with plots in Matplotlib

### Project: "Analysis of Medical Appointment Data in Brazil"

The dataset for analysis contains more than 100,000 medical appointments in Brazil. Each row in the dataset is a medical appointment, which includes the date for which the appointment was scheduled, the actual appointment date, location of the hospital, information about the patient, such as his or her gender, age, health conditions, and social welfare status.

The goal of this project is to find potential trends among the patients who were absent from the appointment, and how they differed from the patients who showed up. Existing and created variables are evaluated and compared to provide statistical description of these two groups and to identify factors for further examination of statistically significant correlations.

---

## Section 2: Practical Statistics

Skills/knowledge learned:
- Binomial Distribution
- Conditional Probability and Bayes Rule
- Standardizing
    - Convert distributions into standard normal distribution using Z-score
    - Compute proportions using standardized distribution
- Sampling Distributions and Central Limit Theorem
- Confidence Intervals
- A/B Test and T-Test
- Regression / Logistic Regression

### Project: "Analyze A/B Test Results"

This project analyzes an A/B test conducted by an e-commerce company. The company developed a new web page and hoped that it would increase the sales through more visits to the page.

The goal of this project is to go through each analysis step and help the company decide if they should implement the new page, keep the old page, or run the experiment longer to make their decision.

---

## Section 3: Data Wrangling

Skills/knowledge learned:

- Gathering data from multiple sources, including programmatically downloading files and accessing data from APIs
- Importing data of various file formats
- Assessing data visually and programmatically
- Identifying data quality issues, such as validity, accuracy, completeness, consistency and uniformity, and categorize them using metrics
- Cleaning data

### Project: "WeRateDogs"

The subject of analysis for this project is WeRateDogs, a popular Twitter account that rates pet dogs with a humorous comment about the dog. Data on WeRateDogs are collected from three different sources and then cleaned before a final analysis on its contents and features.

The three sources of data:
- An archive dataset file of more than 5,000 tweets, which provides information on individual tweet id, text content of the tweet, reply status, re-tweet status, ratings, name and breed of the dog. The information about ratings, dog name and dog stage was extracted programmatically from the text content of the tweet for further cleaning   
- Data on the breed of the dog in the tweet based on image prediction. The data is stored on Udacity’s server and needs to be downloaded programmatically
- Data via the Twitter API on tweet id, retweet count, and favorite count

---

## Section 4: Data Visualization

Skills/knowledge learned:

- Supplementing statistics with visualizations to build understanding of data
- Choosing appropriate plots, limits, transformations and aesthetics to explore a dataset, allowing one to understand distributions of variables and relationships among features
- Using design principles to create effective visualizations for communicating findings to an audience

### Project: "Bike Sharing Service Data Analysis"

This project analyses the use of a bike sharing service in San Francisco - Bay area with the data directly retrieved from the website of the service (https://www.lyft.com/bikes/bay-wheels/system-data). The dataset contains information about individual rides, including start and end station, duration, time, and user information. For the scope of the project, data about more than 2 million bike sharing rides from May 2018 to April 2019 are collected for analysis. New variables are created to look into how the service is used.