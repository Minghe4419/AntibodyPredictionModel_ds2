# AntibodyPredictionModel_ds2
This project aims to test effectiveness of a vaccine by developing prediction models for antibody level.

Understanding antibody responses can help inform vaccine effectiveness and identify populations with weaker immune responses. The antibody level measured via dry blood spot (log-transformed) is the primary outcome of interest. Data considered to be potential predictors to understand factors influencing the antibody response are collected in `dat1.RData`. A few months after the initial data collection, a new, independent dataset `dat2.RData`, with the same structure as `dat1.RData`, for the purpose of evaluating robustness and generalizability of the prediction model.

Variable Name (Column Name)        Description

ID (id)                            Participant ID

Age (age)                          Age (in years)

Gender (gender)                    1 = Male, 0 = Female

Race/ethnicity (race)              1 = White, 2 = Asian, 3 = Black, 4 = Hispanic

Smoking (smoking)                  0 = Never smoked, 1 = Former smoker, 2 = Current smoker

Height (height)                    Height (in centimeters)

Weight (weight)                    Weight (in kilograms)

BMI (bmi)                          Body Mass Index; BMI = weight (kg) / [height (m)]²

Diabetes (diabetes)                0 = No, 1 = Yes

Hypertension (hypertension)        0 = No, 1 = Yes

Systolic blood pressure (SBP)      Systolic blood pressure (mmHg)

LDL cholesterol (LDL)              LDL cholesterol (mg/dL)

Time since vaccination (time)      Time since vaccination (in days)

Log-transformed antibody level     Response variable
(log_antibody)
