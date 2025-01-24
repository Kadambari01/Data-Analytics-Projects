# EMPLOYEE PERFORMANCE ANALYSIS

![image](https://github.com/user-attachments/assets/56cd895c-2c5a-436d-a52c-a73b5faaed01)![image](https://github.com/user-attachments/assets/278e2e5b-f5b9-4a68-9601-1586166eb81a)





### Categorical Features:
1.EmpNumber

2.Gender

3.EducationBackground

4.MaritalStatus

5.EmpDepartment

6.EmpJobRole

7.BusinessTravelFrequency

8.OverTime

9.Attrition


### Numerical Features:

1.Age

2.DistanceFromHome

3.EmpHourlyRate

4.NumCompaniesWorked

5.EmpLastSalaryHikePercent

6.TotalWorkExperienceInYears

7.TrainingTimesLastYear

8.ExperienceYearsAtThisCompany

9.ExperienceYearsInCurrentRole

10.YearsSinceLastPromotion

11.YearsWithCurrManager


### Ordinal Features:

1.EmpEducationLevel

2.EmpEnvironmentSatisfaction

3.EmpJobInvolvement

4.EmpJobLevel

5.EmpJobSatisfaction

6.EmpRelationshipSatisfaction

7.EmpWorkLifeBalance

8.PerformanceRating


## Tools and Library Used:
### Tools:
Jupyter


### Library Used:
* Pandas
* Numpy
* Matplotlib
* Seaborn
* pylab
* Scipy
* Sklearn
* Pickle


## Goal 1: Department Wise Performances

**PLOT USED**

1. Violinplot: It shows the distribution of quantitative data across several levels of one (or more) categorical variables such that those distributions can be compared.
2. CountPlot: countplot is used to Show the counts of observations in each categorical bin using bars.
Sales: The Performace rating level 3 is more in the sales department. The male performance rating the little bit higher compared to female.

* Human Resources: The majority of the employees lying under the level 3 performance . The older people are performing low in this department. The female employees in HR department doing really well in their performance.

* Development: The maximum number of employees are level 3 performers. Employees of all age are performing at the level of 3 only. The gender-based performance is nearly same for both.

* Data Science: The highest average of level 3 performance is in data science department. Data science is the only department where less number of level 2 performers. The overall performance is higher compared to all departments. Male employees are doing good in this department.

* Research & Development: The age factor is not deviating from the level of performance here where different employees with different age are there in every level of performance. The R&D has the good female employees in their performance.

* Finance: The finance department performance is exponentially decreasing when age increases. The male employees are doing good. The experience factor is inversely relating to the performance level.

## Goal 2: Top 3 Important Factors effecting employee performance
The top three important features affecting the performance rating are ordered with their importance level as follows,

1. Employment Environment Satisfaction
2. Employee Salary Hike Percentage
3. Experience Years In CurrentRole

* Employee Enviroment satisfaction: Maximum Number of Employees Performance Rating belongs to EmpEnvironmentSatisfaction Level 3 & Level 4, It contains 367 & 361.

* Employee last salary hike percent: More Number of Employees whose salary hike percentage belongs to 11-19 % are getting 2 & 3 performance rating Maximum time. as well asEmployees whose salary hike percentage is in between 20-22%, There performance rating is 4.

* Employee work life balance: In EmpWorkLifeBalance, level 3 is showing high Performance Rating of employees

## Goal 3: A Trained model which can predict the employee performance
**The trained model is created using the machine learning algorithm as follows with the accuracy score**

1. Support Vector Classifier: 98.28% accuracy
2. Random Forest classifier: 95.61% accuracy
3. Artifical Neural Network [Multilayer percepton]: 95.80%


## Goal 4: Recommendations to improve the employee performance
The overall employee performance can be achieved by employee environment satisfaction. The company needs to focus more on the employee environment satisfaction.
The salary hike will give the boost to the employees to perform well.
Promote the employee ervery 6th month
Improve Employee's work-life balance this affects the performance rating.
While recruiting for HR, consider the female candidates where they perform well compared to male.
The development and sales department is having an overall higher performance comparing to rest of the departments. While some of the employees who gives feedback like Low & Medium from Job Satisfaction & Relationship Satisfaction feature, such employees gives Excellent performance more in number. So company should focus on them.
