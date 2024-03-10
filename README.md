# AB-testing

Good day, this research was made while I was studying in Yandex.

**Purpose**: evaluate the results of the A/B test.

**Stages**: 
1) data loading, data preprocessing
2) data integrity check
3) assessment of the correctness of testing
4) studying user's activity
5) EDA (Exploratory Data Analysis)
6) evaluation of test results
7) conclusions
   
**Stack**: pandas, seaborn, matplotlib, matplotlib_venn, numpy, warnings, scipy.stats, math, plotly, missingno, collections, datetime

**Conclusions**:
1) Checking and preprocessing was carried out in 4 datasets;
2) The testing carried out meets the requirements of the technical specifications;
3) The conversion percentage for group B among recommender_system_test participants at all stages is not lower than 50%;
4) The expected effect of increasing conversion in group B, relative to conversion in group A, is observed;
5) Recommendations were given:
   - do not conduct parallel competing tests;
   - do not conduct tests so that they overlap in time intervals with large marketing events;
   - it is necessary to analyze the scenario of client behavior, since it was found that there are 4,301 variants of user behavior, while 3,030 are managed solely by registration;
