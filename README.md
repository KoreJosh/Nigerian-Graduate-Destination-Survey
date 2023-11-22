# Nigerian Graduate Destination
![](https://github.com/KoreJosh/Nigerian-Graduate-Destination-Survey/blob/main/4l19533-grad.jpg)

# Introduction
Optimizing Educational Infrastructure for Sustainable Employment and Future Success of Nigerian Graduates

# Problem Statement
The eductional infastructure for Nigerian Graduates faces challenges that hinders their sustainable employment and future success. Issues such as limited job mobility, course relevance in the real world, avaliable job opportunities and qualification needed, present obstacles. This analysis aims to look into the employment roadmap for  the past 5 years among Nigerian graduates.

# Data Source
The Data is gotten from kaggle and was gathered by statun ( an online platforms that aims to connect graduates to job opportunities).

# Tools
 Python Jupyter nootbook was used for the analysis while packages such as matplotlib and seaborn was used for visualization and pandas used for dataset manipulation

# Data Cleaning /  Preparation
 - Checked for thr percentage missing data
 - Filled the columns 'Whats your current role' with the Column' Whats your first job after graduation'.
 - For missing entries in the 'NYSC completion' Column filled it with 'No'
 - 
# Exploratory Data Analysis
 The followings insights were answered using the cleaned dataset:
- Top 15 Sectoes:
     most sector where graduates were employed
-  Employment by Gender
-  Income By Degree
-  Most Preferred work Sector
-  Most Studied Course
-  Most Employable Courses over the 5 year span
-  Does extra qualification lead to better Job placement?
-  Number of Jobs after Graduation by Percentage
-  Monthly Income by Degree
-  How Did you find out ABOUT YOUR JOB?
-  Employment Status
-  Nysc Completion

# Result/ Findings>:
 - There was equal representataion of both gender (male and female) in the analysis, also there was no gender bias in employment.
 - 65% of the graduates completed their NYSC program while another 14% are stil
  
# **Data Set Description**

| Column Name                                                      | Description                                                                                                      |
|------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| **Timestamp**                                                        | The date and time when the survey response was recorded.                                                          |
| **What is your gender**                                            | The gender of the survey respondent.                                                                             |
| **Year of graduation**                                               | The year in which the respondent graduated from their educational institution.                                   |
| **Title of course studied**                                          | The name or title of the course or program that the respondent studied.                                           |
| **Polytechnic/University attended**                                  | The name of the educational institution (polytechnic or university) that the respondent attended.               |
| **What is your highest level of education?**                         | The highest level of education attained by the respondent (e.g., Bachelor's, Master's, Ph.D., etc.).              |
| **What best describes your current status?**                         | The current employment or academic status of the respondent (e.g., employed, unemployed, student, etc.).        |
| **How many jobs have you had since graduation including your current one?** | The number of jobs the respondent has held since graduating, including the current one.                |
| **Have you completed your NYSC?**                                    | Whether the respondent has completed the National Youth Service Corps (NYSC) program in Nigeria.              |
| **If you answered yes/ongoing to the previous question, what year did you (or will you) complete your NYSC?** | The year when the respondent completed or plans to complete their NYSC.                         |
| **Did you get your first full-time job through your NYSC placement?**  | Whether the respondent's first full-time job was obtained through their NYSC placement.                      |
| **Thinking about your first employment after graduation, what was your job level?** | The job level or position the respondent held in their first job after graduating.                     |
| **What is/was your job role?**                                       | The job role or position title that the respondent had in their first employment after graduation.             |
| **What sector/industry is your company in? (E.g. Banking, Agriculture, Telecommunication)** | The industry or sector in which the respondent's first employer's company operates (e.g., Banking, Agriculture, Telecommunication, etc.). |
| **Still thinking about your first employment, what is/was your monthly income level?** | The monthly income level of the respondent in their first job after graduation.                      |
| **Did you need your higher education qualification to get your first job (the actual qualification, not the subject of study)?** | Whether the respondent's actual qualification was required to obtain their first job.                |
| **What was the most significant reason for deciding to take your first job?** | The primary reason that influenced the respondent's decision to accept their first job after graduation. |
| **Thinking about your current employment, what is your job level?** | The job level or position that the respondent currently holds in their current employment.               |
| **What is your job role?**                                           | The job role or position title that the respondent currently holds in their current employment.               |
| **What sector/industry is your company in? (E.g. Banking, Agriculture, Telecommunication).1** | The industry or sector in which the respondent's current employer's company operates (e.g., Banking, Agriculture, Telecommunication, etc.). |
| **What is your current monthly income level?**                      | The current monthly income level of the respondent in their current job.                                     |
| **Did you need your higher education qualification to get this job (the actual qualification, not the subject of study)?** | Whether the respondent's actual qualification was required to obtain their current job.          |
| **What was the most significant reason for deciding to take this job?** | The primary reason that influenced the respondent's decision to accept their current job.                 |
| **Which employer in the country do you think offers the best opportunities for graduates?** | The name of the employer or company in Nigeria that the respondent believes provides the best opportunities for graduates. |
| **Reason why?**                                                      | The reasons or justifications for the respondent's choice of the best employer for graduates.                 |
| **Which sector is your most preferred sector to work in?**            | The sector or industry that the respondent prefers to work in.                                                   |
| **What currency are you currently paid in?**                         | The currency in which the respondent is paid for their current job (e.g., Nigerian Naira, US Dollar, etc.).   |
| **Approximately how many hours a day do you currently work?**         | The average number of hours per day that the respondent works in their current job.                            |
| **As far as you are aware, what was most important to your current employer about your qualification?** | The most significant aspect of the respondent's qualification that their current employer considers important. |
| **How do you find out about your job(s)?**                            | The methods or sources through which the respondent learned about their current or past jobs.               |
| **Thinking about your current employment, did you work for your employer before or during your higher education study?** | Whether the respondent worked for their current employer before or during their higher education study.  |
| **Which form of transport do you use the most?**                     | The primary mode of transportation that the respondent uses for commuting or traveling.                        |
| **Were you able to rent an apartment or buy a car from the salary you got from your first job?** | Whether the respondent was able to afford renting an apartment or buying a car with the salary from their first job. |
| **My course of study prepared me well for employment**                | The respondent's perception of how well their course of study prepared them for employment.                   |
| **My course of study prepared me well for further studies**           | The respondent's perception of how well their course of study prepared them for further academic studies.      |
| **Which of these skills/knowledge did your higher education prepare you for?** | A list of skills or knowledge areas that the respondent believes their higher education prepared them for.   |
| **Employed**                                                        | A indicator (Yes or No) to show if the respondent is employed (Yes) or not (No) based on the number of jobs held since graduation. Not based on current status.

## Usage

```jupyter notebook
!wget https://raw.githubusercontent.com/EJmpa/Stat-Solver/main/Data_Cleaning/Nigerian_Graduates_Destination_Survey.csv
```
