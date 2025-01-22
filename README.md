# Project: HR Analytics

## About Practice Problem: HR Analytics
HR analytics is revolutionizing the way human resources departments operate, leading to higher efficiency and better results overall. Human resources have been using analytics for years. However, the collection, processing, and analysis of data have been largely manual, and given the nature of human resources dynamics and HR KPIs, the approach has been constraining HR. Therefore, it is surprising that HR departments woke up to the utility of machine learning so late in the game. Here is an opportunity to try predictive analytics in identifying the employees most likely to get promoted.

### Data Collection
The dataset is sourced from Analytics Vidhya: [WNS Analytics Hackathon 2018](https://datahack.analyticsvidhya.com/contest/wns-analytics-hackathon-2018-1/).

### Problem Statement
Your client is a large multinational corporation (MNC) operating across nine broad verticals. One of the challenges your client faces is identifying the right people for promotions (only for manager positions and below) and preparing them in time. Currently, the process they follow is:

1. Identify a set of employees based on recommendations and past performance.
2. Selected employees undergo a separate training and evaluation program for each vertical, designed based on the required skills of that vertical.
3. At the end of the program, promotions are determined based on various factors such as training performance and KPI completion (only employees with KPIs completed greater than 60% are considered).

The promotions are only announced after the evaluation process, leading to delays in transitions to new roles. The company needs your help in identifying eligible candidates at a specific checkpoint to expedite the promotion cycle.

You are provided with multiple attributes related to employees' past and current performance, along with demographic data. Your task is to predict whether a potential promotee at the checkpoint in the test set will be promoted or not after the evaluation process.

### Dataset Description

| Variable                | Definition                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| `employee_id`           | Unique ID for employee                                                   |
| `department`            | Department of employee                                                   |
| `region`                | Region of employment (unordered)                                         |
| `education`             | Education Level                                                         |
| `gender`                | Gender of Employee                                                      |
| `recruitment_channel`   | Channel of recruitment for employee                                      |
| `no_of_trainings`       | Number of other trainings completed in the previous year on soft skills, technical skills, etc. |
| `age`                   | Age of Employee                                                        |
| `previous_year_rating`  | Employee Rating for the previous year                                    |
| `length_of_service`     | Length of service in years                                              |
| `KPIs_met >80%`         | If percent of KPIs (Key Performance Indicators) >80% then 1 else 0      |
| `awards_won?`           | If awards won during the previous year then 1 else 0                    |
| `avg_training_score`    | Average score in current training evaluations                           |
| `is_promoted`           | (Target) Recommended for promotion                                      |

### Evaluation Metric
The evaluation metric for this competition is the **F1 Score**.

### Public and Private Split
The test data is further randomly divided into Public (40%) and Private (60%) data:

- Your initial responses will be checked and scored on the Public data.
- The final rankings will be based on your Private score, which will be published once the competition is over.


### Dependencies
The following Python libraries are required for this project:

- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **Scikit-learn**: Machine learning tools
- **Jupyter Notebook**: Interactive environment for running and documenting the project


