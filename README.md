# Social_Justice_in_Programming

This project examines how equal opportunities are to be successful as a developer based on the stackoverflow survey from 2017.
The analysis is performed as part of the Udacity training - Data Scientist Nanodegree.

About my motivation: 
Social justice is an extremely important topic in which humanity still has a lot of room for improvement. 
I wanted to use this project to investigate how equal opportunities are in the job profile of professional programmers.


## Installation

The Jupyter Notebook is written in python 3.9.7.

The required libraries to run the notebook are:
```bash
pip install pandas seaborn matplotlib numpy
```


## File Descriptions

All analysis resides in the Jupyter Notebook. The notebook contains cells of text so it should be readable chronologically.
*SocialJusticeInProgramming.ipynb*

The database on which the analysis is based is the StackOverflow survey from 2017 (*2017survey_results_public.csv*).
The questions asked in the survey can be found in the schema (*2017survey_results_schema.csv*). 


## Project insights and Results

The analysis is based on the following three questions:
- Q1 Is there equal opportunity in the programming profession?

- Q2 How does your social environment influence your chances of being successful as a developer? 

- Q3 How important is an open mind and tolerance to succeed as a programmer? 

After an overview of the database is given, the questions are processed chronologically in the notebook.
I also tried to predict how much a person would earn based on race, parental education, gender, and country. 
The idea behind it was: If it is possible to predict how much a person earns based on these few parameters 
that cannot be influenced or can only be influenced to a limited extent, this would be a questionable result for mankind.
Fortunately, I was not able to do this with a linear regression model from seaborn, nor with a simple dense model from Keras.
In the Git repo is a "tried out fitting some models" commit. 
Feel free to go back to this one and try if you have more success in predicting.

The summarized results for the three questions are:
Q1:
Overall, we can state that ethnicity has the greatest impact on the level of satisfaction achieved. 
As the graphics show, all initial conditions have an impact on salary and satisfaction. 
Question Q1 can be clearly answered in the negative. **There is no equal opportunity in the job profile of professional developers.**

Q2:
With regard to Q2, it can be said that the social environment has a significant impact on success as a programmer. 
The parents in particular have a major impact. The higher the educational level of the parents, 
the more likely it is to achieve a high salary and the greater the chances of being satisfied in one's job/career.
As far as the circle of friends is concerned, it is advantageous in terms of salary not only to surround oneself
with friends of the same professional orientation. However, this parameter is irrelevant for the level of satisfaction achieved.

Q3:
To answer Q3, it is important to note that it is extremely important to be open to different solution approaches when it comes to maximizing salary. <br>
In addition, a clear opinion can help to maximize the salary. It should be taken into account that open people are happier.


For more information check out: https://medium.com/@florianpue/an-inconvenient-truth-about-social-justice-in-programming-f78fb17c614b

## Author
Author: Florian Pütz, florian.puetz@dlr.de


## Data Source
https://insights.stackoverflow.com/survey