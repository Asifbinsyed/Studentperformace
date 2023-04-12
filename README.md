# End to End Machine Learning Project
This end to end machine learning project will predict the student performance from several variable 
![Banner!](https://github.com/Asifbinsyed/Studentperformace/blob/main/image/Predict_student_performance_using_machine_learning.png)

<div id="badge-container">
  <a href="https://www.linkedin.com/in/asifbinsyed/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="">
    <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Youtube Badge"/>
  </a>
  <a href="your-twitter-URL">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>

### Problem statement
- This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.


### Data Collection
- Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
- The data consists of 8 column and 1000 rows.

### Exploratory data Analytics

#### Histogram plot based on the gender

![Histogram!](https://github.com/Asifbinsyed/Studentperformace/blob/main/image/histogram_based_on_gender.png)

*insight:* Female tends to do better in the exam

#### Histogram plot based on the other varibles
![Histogram other!](https://github.com/Asifbinsyed/Studentperformace/blob/main/image/histogram_for_other_varibles.png)
- Standard lunch helps perform well in exams.
- Standard lunch helps perform well in exams be it a male or a female.
#### Pairplot for genders
![pair plot!](https://github.com/Asifbinsyed/Studentperformace/blob/main/image/pairplot.png)

- From the above plot it is clear that all the scores increase linearly with each other.

#### R2_ Scores for the model

| Model Name              | R2_Score | Rank |
| ----------------------- | -------- | ---- |
| Ridge                   | 0.880593 | 2    |
| Linear Regression       | 0.879226 | 0    |
| Random Forest Regressor | 0.852189 | 5    |
| CatBoosting Regressor   | 0.851632 | 7    |
| AdaBoost Regressor      | 0.846089 | 8    |
| Lasso                   | 0.825320 | 1    |
| XGBRegressor            | 0.821589 | 6    |
| K-Neighbors Regressor   | 0.783813 | 3    |
| Decision Tree           | 0.756574 | 4    |



### requirement for running the code
Install my-project with npm

```bash
  pip install -r requirement.txt
```
    

## Acknowledgements

 - [End to End Machine learning By Krish](https://www.youtube.com/playlist?list=PLZoTAELRMXVPS-dOaVbAux22vzqdgoGhG)

<style>
  .scroll-container {
    overflow-y: auto;
    max-height: 100px;
  }
</style>

<div class="scroll-container" markdown="block">
  This is the content you want to have a scrolling feature.
   These following graphs and plots were primarily created using Matplotlib and the Seaborn package.
 - Bar plot, count plot, pair plot, dist plot, box plot, nad heatmap
 
 Performed EDA and reached the following conclusions:
 - The average client is between the ages of 25 and 60, but the majority of bank term deposits are made by clients between the ages of 30 and 36.
 - Most clients with blue-collar jobs do not subscribe to bank term deposits (20.52%), but most clients with managerial jobs do (2.88%).
 - Most of the clients are married. Clients who are married are the most likely to subscribe to term deposits, and they are also the least likely to subscribe to term deposits.
 - Most of the clients are married. Clients who are married are the most likely to subscribe to term deposits, and divorced clients are less likely to subscribe to term deposits.
 - Clients who are more educated than the primary are more likely to sign up for a term deposit.
 - Most of the clients who subscribed to term deposits have no credit in default.
 - The majority of clients who have signed up for a term deposit do not have any housing loan.
 - If a client has a housing loan, there is a 51% chance that they will not subscribe to a term deposit.
 - Clients are more likely to subscribe to the term deposit if they do not have any personal loans.
 - If the client has a personal loan, there is a greater chance that they will not subscribe to a term deposit.
 - The clients who were contacted with celluler are mostly subscribed to term deposits.
 - Less than one percent of total clients contacted per day subscribe to term deposits.
 - In May, June, July, August, and April, more than 1 percentage of clients subscribed to the term deposit, but other than this month,
 less than 1 percentage of clients subscribed to the term deposit.
 - In June, July, August, and April, more than 1 percentage of clients subscribed to the term deposit, but other than this month,
 less than 1 percentage of clients subscribed to the term deposit. May's subscriber rate is more than double that of the other months of the
 year, a difference of more than 2 percentage.
 - No one has signed up for term deposit if they have received more than three phone calls. Less than three times contacted clients who signed up for term deposits.
 - Only 11.7% of total clients sign up for term deposits, which means that there is an 88.3% chance that clients will not subscribe to term deposits.
 - Most clients who have management-related jobs and a tertiary degree have subscribed to the term deposits.
 - Customers with a secondary education are the second most likely to subscribe to term deposits.
 - Clients are more likely to subscribe to term deposits if they spend more time on the phone.
 - Average of 400 seconds required to convey clients' intent to subscribe and make a term deposit
 - A customer is more likely to sign up for a term deposit if he is entirely debt-free.
 - Customers are less likely to choose a term deposit if they already have both types of loans.
</div>