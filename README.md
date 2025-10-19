# ELarson Education Project DATA 5100
## Exploring Socioeconomic and Regional Factors and Their Influence on U.S. High School Educational Outcomes


> This project used data science methodology to explore how socioeconomic factors and regional differences impact educational opportunities in U.S. high schools. Specifically, it used 5 measures of socioeconomic value (unemployment rate, percent adults with college degree, percent children in married couples family, median household income, and percent eligible for free and reduced lunch), with an additional look at regional differences, to determine their value in predicting average ACT scores. The project used socioeconomic data and average ACT scores from EdGap.org and basic school information from the National Center for Education Statistics.

---

## Project Overview

This project explored the impact of socioeconomic and regional predictors on U.S. high schools, using the measurement of average ACT scores and the response variable. A multiple linear regression model was fit using the predictors unemployment rate, percent of adults with college education, median income, parent marriage status, student eligible for free or reduced price lunch, and US region. The analysis discovered that free or reduced price lunch eligibility was the strongest predictor of average ACT score. Other significant predictors were percent adults with college education and unemployment rate. Regional influence was minimal. Median income and parent marriage status were not significant. The results indicate that school-level measurements of socioeconomic predictors are better explanatory variables for predicting average ACT scores than broader area measurements. 

- **Objective:** Determine if socioeconomic and regional factors predict ACT and SAT scores. 
- **Domain:** Social Science, Education
- **Key Techniques:** Regression

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
└── README.md             # Project documentation
```

---

## Data

- **Source:**
- CCD Data: https://nces.ed.gov/ccd/pubschuniv.asp
- EdGap Data: https://www.edgap.org/#6/36.987/-106.705

---

## Analysis

The code for the project is in the notebook titled Education Project.

---

## Results

The project demonstrated that socioeconomic factors, especially the percentage of students eligible for free or reduced price lunch, are strong predictors of the average ACT score in U.S. high schools. The region of the high school has a small influence. While other factors like parental education and unemployment rate also showed significant relationships, variables such as median income and marital status of parents did not meaningfully improve the model. This suggests that school level measurements of student socioeconomic wellbeing are more effective at explaining academic outcomes than broader measurements.

---

## Authors

- Emily Larson - elarson5 (https://github.com/elarson5)

---

## Acknowledgements

- Tools/libraries used: Jupyter Notebook
- DATA 5100 lessons

