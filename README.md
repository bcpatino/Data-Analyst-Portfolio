# Salary Analysis


## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results/findings)
- [Recommendation](#recommendation)
- [Limitations](#limitations)
- [References](#references)
  
### Project Overview

This project aims to identify the factors that define the employee salaries based on the given dataset.

### Data Sources

[Kaggle](https://www.kaggle.com/datasets/mohithsairamreddy/salary-data)

### Tools

- Analysis: Microsoft Excel  [Download here](https://microsoft.com)
- Visualization: Microsoft Excel
- Final Report: Microsoft Powerpoint

### Data Cleaning and Preparation

1. Data Loading and Review - The csv file of the dataset was obtained from Kaggle and was analyzed in Excel. After the content was reviewed, planning of the analytical approach followed.
2. Data Cleaning - The dataset contained:
- null values – eliminated as it as irrelevant to the analysis
- inconsistent values – corrected
- irrelevant column – deleted
- outliers – 4 value deleted
- duplicate values - 2 duplicates were removed
3. Analysis - Excel was used to run descriptive analysis of the dataset. Visualization was also done in Excel.Final report is in Powerpoint.

### Exploratory Data Analysis (Questions you asked)

- What is the educational attainment distribution per gender?
- Is there a correlation between year of experience and salary?
- What is the average salary per gender?
- What is the average salary per educational attainment?
- Does salary commensurate with age?
- What is the average salary per age bracket?

### Data Analysis
```Excel
 = CORREL([Salary], [Educational Attainment])
 = CORREL ([Salary], [Age])
```

### Results/Findings

1. Gender
   - Male people receive the highest salaries than other-gender and female
2. Educational Attainment
   - PhD degree holders have the highest average salaries at around P160,000.00. Highschool graduates receive the least.
3. Years of Experience
   - There is a strong positive correlation between salary and years of experience. The longer the work years, the higher the salary.
4. Age
   - Most senior employees showed the highest average salaries. This is supported by the positive correlation between the two measures. As employees age, their salary increases.

### Recommendation

From the dataset and analysis done, the factors determining salary levels are:
1. Educational Attainment – higher degrees tend to receive higher salaries
2. Gender – Males receive more than females and other genders. The type of work is a good differentiation factor for this result.
3. Years of Experience – the more seasoned employees receive higher salaries probably due to higher positions in the company.
4. Age – As an employee ages, salary also increases which is an indication of career growth.

### Limitations

- only a descriptive analysis was performed in this project
- the column "Job Title" was excluded as the variety of jobs are too big to create a collective conclusion
- 4 outlier values in the Salary column were deleted as the values can mislead the analysis
- Null values were imputed as its values cannot be supplemented accurately

### References

1. [Interview Query](https://www.interviewquery.com/p/data-analytics-project-ideas-and-datasets#beginner-data-analytics-projects)


 
