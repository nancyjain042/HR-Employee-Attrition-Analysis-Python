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



 **Exploratory Data Analysis (EDA)**: We perform in-depth EDA to uncover hidden patterns, correlations, and trends related to employee attrition. To understand the central tendencies of numerical attributes, I calculated the mean values for each of them, revealing insights into the dataset's overall characteristics. Usage of median, for loops and lambda functions were also done.

 
 **Data Visualization**:
 We leverage popular Python libraries like Matplotlib and Seaborn to create informative and visually appealing charts and graphs that illustrate attrition patterns. We have generated a diverse set of visualizations, including pie charts, line charts, bar charts, a correlation matrix, and several other graphical representations. These visualizations serve the purpose of analyzing relationships between different factors within the dataset and extracting valuable insights



### Insights
1. The organization's attrition rate stands at 16.12%, indicating a notable departure of employees.
Notably, young professionals constitute a significant portion of those leaving, highlighting a demographic trend.

2. Although the Research and Development department has the highest number of employees, the Sales department experiences the highest attrition rate, reaching approximately 21%.
  
3. **Income Disparity**: Employees who are leaving the company have an average monthly income approximately $2000 less than those who are staying. This income disparity suggests that pay gap might be a contributing factor to the attrition rate.

4. **Gender Pay Equality**: Encouragingly, there is no evidence of a pay gap between genders within the organization. This demonstrates gender pay equality, indicating fair compensation practices.

5. **Gender Diversity**: The company maintains a diverse employee profile, with approximately 60% males and 40% females. This diversity can foster an inclusive work environment and contribute to a balanced workforce.

6. Overtime (45% attrition rate) and the Sales Representative role with a 40% attrition rate, stand out as major contributors to employee turnover.

7. Attrition is most pronounced among employees with 23 years of service, closely followed by freshers with 0-2 years of experience, suggesting potential issues at both ends of the experience spectrum.

8. Jobs that require frequent travel are associated with a 25% attrition rate, underscoring the impact of travel demands on employee retention.


### Recommendations
1. Pay Equity: Address the income disparity observed between employees leaving and staying in the company. Investigate potential pay gap issues to ensure fair compensation practices across all levels.

2. Overtime and Role Analysis: Investigate the causes of high attrition associated with overtime (45%) and the Sales Representative role (40%). Consider workload management strategies and career development opportunities to retain employees in these roles.

3. Experience Spectrum: Recognize attrition trends at both ends of the experience spectrum, with employees completing 23 years of service and freshers (0-2 years) leaving the company. Tailor retention strategies  to address specific concerns of these groups.

4. Travel-Related Attrition: To mitigate the impact of travel demands on employee retention (25% attrition rate), consider flexible work arrangements, incentives, or support mechanisms for employees in roles requiring frequent travel.

5. Training and Development: Invest in training and development programs for employees at all career stages, from freshers to long-serving staff. This can improve skills, job satisfaction, and retention rates.

6. Flexible Work Arrangements: Offer flexible work arrangements, such as telecommuting options or flexible hours, to help employees better manage their work-life balance. This can reduce the burden of overtime and potentially mitigate attrition.

7. Exit Interviews: Conduct thorough exit interviews with departing employees to gain insights into their reasons for leaving. Use this feedback to refine retention strategies and address specific pain points.

8. Mentorship and Support: Establish mentorship programs to help new employees, including freshers, acclimate to the organization. Providing guidance and support can improve their job satisfaction and long-term commitment.


### Installation
To run the analysis, you need Python 3 and the following Python libraries:
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
