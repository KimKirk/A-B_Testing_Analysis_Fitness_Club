# A-B_Testing_Analysis_Fitness_Club
A/B Testing Analysis Fitness Club Acquisition Funnel

- A/B Testing: Fitness Club - Marketing Analytics

- Descriptive and inferential data analyses were performed on the A/B test results for a fitness club's acquisition funnel. 5,004 rows were imported, cleaned, and analyzed. The analysis showed with confidence (statistical significance) several results. For Stage 1 of the acquisition funnel there is a higher percentage of visitors who apply for a gym membership that do not take the fitness test. For Stage 2 of the acquisition funnel, for visitors who did turn in an application, it seems that there are not more people who took the fitness test who also purchased a gym membership. For the Stage 3 (the final stage of the acquisition funnel), looking at all visitors to the gym, there were more visitors who did not take the fitness test who also purchased a gym membership. The business recommendation is that incorporating a fitness test into the acquisition funnel for gym membership does not seem to help the process.

- 5004 rows of data set that includes 9 features.

- [Presentation Here](https://docs.google.com/presentation/d/e/2PACX-1vQ1wpMLYn_tlMU8DjBwFLLrwxODtyQ-Yn0uHIyGVnNA6EugmanfVsLmeL2SzHEnEaEt-5jsuYaQy4iU/pub?start=false&loop=false&delayms=3000)
- [Report Here](https://drive.google.com/file/d/1qVHRBXMymqT3A64ZtYvbUPyV5jXfaOJL/view?usp=sharing)

## Processing Instructions:
- To improve reproducibility of the data analysis, a Jupyter Notebook file, data source files, Python modules are included.

## Steps to Transformation:
- [Data download](https://content.codecademy.com/programs/intro-data-analysis/biodiversity.zip)
- Files “codecademySQL.py” and “codecademySQL.pyc” were imported into Jupyter Notebook for SQL query creation.
- Combined 4 csv files (“visits.csv”, “fitness_tests.csv”, “applications.csv”, “purchases.csv”) into a single data frame.
- Re-code fitness_test_date into categories “A” and “B” for ease of readability and analysis.
- Create new column ab_test_group for frequency count for ab_test_group.
- Recode values into categories "application" and "no application" for ease of readability and analysis.
- Recode values into categories "member" and "not member" for ease of readability and analysis.
- Create new column with application frequency count.
- Create new column “Percent With Application” for percentage visitors who submitted applications.
- Create new column “Percent Membership” for percentage visitors who submitted applications and purchased club membership.
- Create new column “Percent Purchase” for percentage visitors who purchased club membership regardless of application status.
