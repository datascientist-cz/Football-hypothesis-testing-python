# Football-hypothesis-testing-python
Hypothesis testing: analyzing football matches
You can see the project in my personal website https://www.datascientist.cz/portfolio/hypothesis-testing-analying-football-matches/ 
See also my Datacamp Workspace https://app.datacamp.com/workspace/w/03cf8e4e-fcbd-40b6-8d7d-a5ac228ce723/edit
ABOUT THE PROJECT
This is a short Python project demonstrating how to conduct hypothesis testing. It involves brief data wrangling tasks such as handling NaN values, changing data types, and filtering dataframes. Additionally, it includes a concise Exploratory Data Analysis, checking the normality of the data, and utilizing boxplots and histograms. The hypothesis under examination is whether Women’s football matches have a greater average total score (H1) or if the average total score is the same for men’s and women’s matches (H0). The significance level required was set at 10% (alpha=0.01). The analysis focused on matches from the year 2002 onwards to avoid noise caused by changes in style or quality over time. Furthermore, to mitigate variability stemming from different player qualities across organizations, the analysis was restricted to FIFA World Cup matches.

DATA SOURCE
The data for this project has been provided by DataCamp (My datacamp Workspace)

RESULTS
Due to the non-normal distribution of the data, I opted for the Wilcoxon-Mann-Whitney test to compare the averages of women’s and men’s scores. This non-parametric test is more suitable than the Student’s t-test when data are not normally distributed or when there is an insufficient amount of data. The p-value for the one-tailed non-parametric test was 0.0051. Therefore, at alpha=0.01, the null hypothesis can be rejected. We can conclude that, on average, women score more goals when playing football.
