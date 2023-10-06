# Employee Attrition Analysis

### Problem Statement:

The HR department of the organization is focused on understanding and mitigating workforce attrition. The goal is to identify the key factors that influence employees' decisions to leave or stay with the company and to develop actionable insights to improve employee retention. 

### About Dataset
The available dataset contains various data points about past and current employees, including demographics, job-related factors, and employee satisfaction metrics.
The dataset includes the following features:

Age: Employee's age.

BusinessTravel: Frequency of business travel (e.g., Travel_Rarely, Travel_Frequently)

DailyRate: Daily rate of pay

Department: Employee's department (e.g., Sales, Research & Development)

DistanceFromHome: Distance from the employee's home to the workplace

Education: Employee's education level (ranging from 'Below College' to 'Doctor')

EducationField: Field of education

EnvironmentSatisfaction: Satisfaction with the work environment

Gender: Employee's gender

HourlyRate: Hourly rate of pay

JobInvolvement: Level of job involvement

JobLevel: Employee's job level

JobRole: Employee's job role

JobSatisfaction: Job satisfaction level

MaritalStatus: Marital status of the employee

MonthlyIncome: Monthly income of the employee

MonthlyRate: Monthly rate

NumCompaniesWorked: Number of companies the employee has worked for

Over18: Indicates if the employee is over 18 years old

OverTime: Whether the employee works overtime

PercentSalaryHike: Percentage increase in salary

PerformanceRating: Performance rating

RelationshipSatisfaction: Satisfaction with work relationships

StandardHours: Standard working hours

StockOptionLevel: Stock option level

TotalWorkingYears: Total years of work experience

TrainingTimesLastYear: Number of training sessions attended last year

WorkLifeBalance: Work-life balance satisfaction

YearsAtCompany: Number of years with the current company

YearsInCurrentRole: Number of years in the current role

YearsSinceLastPromotion: Number of years since the last promotion

YearsWithCurrManager: Number of years with the current manager

Attrition: The target variable indicating whether the employee has left the company (Yes/No)

### Key Objectives

**Identify Attrition Drivers**: Determine the primary factors that contribute to employee attrition within the organization. Explore the dataset to find patterns and correlations between employee attributes, job-related factors, and attrition status.

**Employee Segmentation**: Segment the workforce based on attributes such as education, job involvement, job satisfaction, and more to understand which groups are more susceptible to attrition.

**Actionable Insights**: Provide actionable recommendations to the HR department on strategies and interventions that can help reduce attrition. These recommendations should be based on the analysis and insights derived from the dataset.


### Data Processing

**Data Exploration**: We preprocess and explore the dataset to gain insights into employee attrition trends. 
1. Dataset Size: The dataset contains 1470 rows, representing individual observations or employees, and 35 columns, capturing various attributes related to these employees.

2. Data Types: Out of the 35 columns, 9 are categorical variables, while the remaining columns are numerical in nature.

3. Missing Values: There are no missing values in any of the columns. This simplifies data preprocessing since no imputation or removal of missing data is required.

4. Duplicates: The absence of duplicates in the dataset ensures data integrity, as each row represents a unique employee record.

5. Outliers: The dataset doesn't contain any outliers, which are extreme or unusual values that can distort statistical analysis



 **Exploratory Data Analysis (EDA)**: We perform in-depth EDA to uncover hidden patterns, correlations, and trends related to employee attrition.

 
 Data Visualization

**Matplotlib and Seaborn**: We leverage popular Python libraries like Matplotlib and Seaborn to create informative and visually appealing charts and graphs that illustrate attrition patterns.

**Interactive Visuals**: Our analysis includes interactive visualizations to provide an engaging experience for exploring the data.


### Insights

### Recommendations

### Installation
To run the analysis, you need Python 3 and the following Python libraries:
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
