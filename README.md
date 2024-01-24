Predicting Recurrence-Free Survival in Node-Positive Breast Cancer Patients: A Survival Analysis using Multiple Imputation

The research aims to investigate the prognostic factors influencing recurrence-free survival in breast cancer patients. To develop a prognostic time-to-event model to assess the impact of various clinical and pathological factors on recurrence-free survival in patients with primary node-positive breast cancer. To identify significant prognostic factors and to assess the effects of hormonal therapy. 

The research will employ multiple imputations to handle missing data and backward elimination to identify significant prognostic factors. A Cox proportional hazard model will be fitted on the imputed dataset, adjusting for significant prognostic factors. Hormonal therapy showed a significant positive effect on recurrence-free survival time, with a 36.5% lower risk of recurrence than those who did not undergo the treatment. Other significant prognostic factors include progesterone receptor, tumour size, tumour grade and transformation of number of positive nodes. 


The dataset used in this study was collected from the German Breast Cancer Study Group between July 1984 and December 1989 for a Comprehensive Cohort Study is used in this research.

Dataset Used:
-------------
- No. of participants : 686
- Can be found at : assessment.rds

Dataset Variables :
-------------------

| Variable  | Description                                          |
|-----------|------------------------------------------------------|
| id        | ID of study participants                             |
| hormon    | Indicator of hormonal therapy (0 no, 1 yes)          |
| age       | Age in years                                         |
| menostatus| Menopausal status (1 premenopausal, 2 postmenopausal)|
| tsize     | Tumour size in mm                                    |
| tgrade    | Tumour grade (1 > 2 > 3)                             |
| posnodes  | The number of positive lymph nodes                   |
| progrec   | Progesterone receptor, fmol                          |
| estrec    | Estrogen receptor, fmol                              |
| rectime   | Recurrence free survival in days                     |
| recyear   | Recurrence free survival in years                    |
| censrec   | Censoring indicator (0 censored, 1 event)            |
| x4a       | Indicator of tumour grade ≥ 2                        |
| x4b       | Indicator of tumour grade = 3                        |
| x5e       | Transformation of number of positive nodes, exp(−0.12 × posnodes) |

Git Version controlled :
------------------------

The following commands are used to version control using git :
(given git is already installed)

1. git init - to initialise a local git repository
2. git add . - to add all the files to be tracked by git
3. git commit -m "comments" - to commit the files and changes to staging area.
5. git remote add origin <link to main>
4. git push -u origin main

Increase the global Git buffer size to the largest individual file size
Optional: git config http.postBuffer 157286400 

RStudio :
--------

Used to create and run the scripts in .rmd file
  

