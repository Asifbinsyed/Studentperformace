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