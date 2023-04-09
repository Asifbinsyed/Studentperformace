# End to End Machine Learning Project
This end to end machine learning project will predict the student performance from several variable 
![Banner!](https://github.com/Asifbinsyed/Studentperformace/blob/main/Student.png?raw=true)

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

#### Pairplot for genders
![pair plot!](https://github.com/Asifbinsyed/Studentperformace/blob/main/image/pairplot.png)




Rank 	Model Name	R2_Score	
2	Ridge	0.880593
0	Linear Regression	0.879226
5	Random Forest Regressor	0.852189
7	CatBoosting Regressor	0.851632
8	AdaBoost Regressor	0.846089
1	Lasso	0.825320
6	XGBRegressor	0.821589
3	K-Neighbors Regressor	0.783813
4	Decision Tree	0.756574



|                         | Model Name | R2_Score | 2 | 0 | 5 | 7 | 8 | 1 | 6 | 3 | 4 |
| ----------------------- | ---------- | -------- | - | - | - | - | - | - | - | - | - |
| Ridge                   | 0.880593   |
| Linear Regression       | 0.879226   |
| Random Forest Regressor | 0.852189   |
| CatBoosting Regressor   | 0.851632   |
| AdaBoost Regressor      | 0.846089   |
| Lasso                   | 0.825320   |
| XGBRegressor            | 0.821589   |
| K-Neighbors Regressor   | 0.783813   |
| Decision Tree           | 0.756574   |