## Sobre o Dataset

O dataset a ser utilizado é o *IBM HR Analytics Employee Attrition & Performance*, disponível no Kaggle. O dataset contém informações sobre funcionários de uma empresa fictícia, como idade, gênero, estado civil, nível de satisfação, entre outros.

[Link do Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data)

O termo *attrition* ("atrito") é frequentemente usado de forma intercambiável no contexto de recursos humanos e gestão de força de trabalho, mas ele se refere a conceitos ligeiramente diferentes em relação às mudanças no número e na composição dos empregados dentro de uma organização. 

### Questionamentos? 

1. Qual é o percentual e quantidade de funcionários que permaneceram e saíram da empresa?
2. Das pessoas que permanecem na empresa, quais são os cargos com mais funcionários?
3. Como está a distribuição de Idade por gênero e status? 
   Status neste caso é Attrition ("No" => Não saiu da empresa  / "Yes" => Saiu da empresa)
4. Qual o total de funcionários que saíram ou não da empresa por tempo de casa?


|    | Name                       | Description                                                                                                                                                    |
|---:|:---------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  0 | Age                        | Numerical Value                                                                                                                                                |
|  1 | Attrition                  | Employee leaving the company - Text - No, Yes                                                                                                                     |
|  2 | BusinessTravel            | Text - Non-Travel, Travel_Frequently, Travel_Rarely                                                                                                             |
|  3 | DailyRate                 | Numerical Value - Salary Level                                                                                                                                 |
|  4 | Department                 | Text - Sales, Research & Development, Human Resources                                                                                                         |
|  5 | DistanceFromHome         | Numerical Value - the distance from work to home in miles 
|  6 | Education                  | Numerical Value - 1=Below college, 2=College, 3=Bachelor, 4=Master, 5=PhD   |
|  7 | EducationField            | Text - Life Sciences, Medical, Marketing, Techincal Degree, Human Resources, Other                                                                                   |
|  8 | EmployeeCount             | Numerical Value - 1                                                                                                                                               |
|  9 | EmployeeNumber            | Numerical Value - Employee ID                                                                                                                                  |
| 10 | EnvironmentSatisfaction    | Numerical Value - 1=Low, 2=Medium, 3=High, 4=Very High |
| 11 | Gender                     | Text - Female, Male                                                                                                                                             |
| 12 | HourlyRate                | Numerical Value - Hourly Salary                                                                                                                                |
| 13 | JobInvolvement            | Numerical Value - 1=Low, 2=Medium, 3=High, 4=Very High                                                                                                         |
| 14 | JobLevel                  | Numerical Value - 1, 2, 3, 4, 5. Means different job levels                                                                                                     |
| 15 | JobRole                   | Text - Sales Executive, Research Scientist, Laboratory Technician, Manufacturing Director, Healthcare Representative, Manager, Sales Representative, Research Director, Human Resources |
| 16 | JobSatisfaction           | Numerical Value - 1=Low, 2=Medium, 3=High, 4=Very High                                                                                                         |
| 17 | MaritalStatus             | Text - Single, Married, Divorced                                                                                                                                      |
| 18 | MonthlyIncome             | Numerical Value - Monthly Salary                                                                                                                               |
| 19 | MonthlyRate                | Numerical Value - Monthly Rate                                                                                                                                  |
| 20 | NumCompaniesWorked        | Numerical Value - Number of companies worked at                                                                                                                |
| 21 | Over18                    | Text - Y                                                                                                                                                    |
| 22 | Overtime                   | Text - No, Yes                                                                                                                                                    |
| 23 | PercentSalaryHike        | Numerical Value - Percentage increase in salary                                                                                                                |
| 24 | PerformanceRating         | Numerical Value - 1=Low, 2=Good, 3=Excellent, 4=Outstanding                                                                                                    |
| 25 | RelationshipSatisfaction  | Numerical Value - 1=Low, 2=Medium, 3=High, 4=Very High                                                                                                         |
| 26 | StandardHours             | Numerical Value - 80                                                                                                                                            |
| 27 | StockOptionsLevel        | Numerical Value - 0, 1, 2, 3                                                                                                                                    |
| 28 | TotalWorkingYears        | Numerical Value - Total years worked                                                                                                                            |
| 29 | TrainingTimesLastYear   | Numerical Value - How many times the employee has been trained last year                                                                                       |
| 30 | WorkLifeBalance          | Numerical Value - 1=Bad, 2=Good, 3=Better, 4=Best                                                                                                              |
| 31 | YearsAtCompany           | Numerical Value - Number of years at the company                                                                                                                |
| 32 | YearsInCurrentRole      | Numerical Value -Number of years in current role                                                                                                                |
| 33 | YearsSinceLastPromotion | Numerical Value - Years since last promotion                                                                                                                    |
| 34 | YearsWithCurrManager | Numerical Value - Years with current manager                                                                                                                    |
