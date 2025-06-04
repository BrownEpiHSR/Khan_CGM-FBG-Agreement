# Khan_CGM-FBG-Agreement
Khan et al. -Agreement Between Fingerstick Blood Glucose and Continuous Glucose Monitor Measures Among Long-Term Care Facility Residents

# Description
This repository contains data documentation and code for the analysis in the manuscript titled "Agreement Between Fingerstick Blood Glucose and Continuous Glucose Monitor Measures Among Long-Term Care Facility Residents."
## Repository Contents
- `data_documentation/` - Contains files describing the data sources, and key variables
- `code/` - The programs used for data management and analysis.
- `LICENSE` - The license under which this repository is shared.
- `README.md` - This file, provides an overview of the repository.
## Data Documentation
The `data_documentation/` directory contains the following files:
Data_Documentation.xlsx- Contains informatiion of the project, data sources, and description of key variables.xlsx 

## Code
The code/ directory contains the following programs:

CGM_macro_altered.sas---Create day-level and day-interval level CGM datasets for each resident>
Fingerstick_macro_altered.sas---Create day-level and day-interval level fingersticks datasets for all residents combined
Day-level and person-level analyses.sas---Conduct day- and person-level analysis of CGM and fingerstick data
Interval-level analyses (Overall).sas---Conduct interval- level analysis of CGM and fingerstick data
CGM_macro_allevents.R---Create a macro that will process excel sheets containing CGM data of residents and create sas datasets, with an indicator for hypoglycemia for every CGM record
Fingerstick_macro_allevents.sas---Create a macro that will process excel sheets containing FBG data of residents and create sas datasets, with an indicator for hypoglycemia for every CGM record
Number of hypoglycemia events per person.sas---Calculate the number of hypoglycemia events per resident captured by CGM and FBG and create a scatter plot
Time of day stratified analysis.sas---Calculate diagnosistic measures and difference in time between CGM-FBG pairs stratified by times of day: 10:00 pm – 5:59 am, 6:00 am – 1:59 pm, and 2:00 pm – 9:59 pm
Time difference_lowest FBG-nearest CGM_8hour overall.sas---Calculate difference in time between pairs of the CGM-FBG measures within 8-hour intervals (of 12:00 am – 7:59 am, 8:00 am – 3:59 pm, and 4:00 pm – 11:59 pm) with the lowest glucose value and the nearest CGM measure in time (regardless of the glucose value, i.e., not necessarily the lowest)
Time difference_lowest FBG-nearest CGM_day-level.sas---Calculate difference in time between pairs of the CGM-FBG measures at the day-level, with the lowest glucose value and the nearest CGM measure in time (regardless of the glucose value, i.e., not necessarily the lowest)
Statistics on the number of CGM and FBG readings.sas <Calculate statistics on the number of CGM and FBG readings per resident, and per resident per day
Demographics_cohort 2.sas---Obtain demographic statisitics for the cohort 2
Phi correlations in R---Calculate the phi correlations and associated confidence intervals for cohort 2; person, day and interval level analyses
Programs were run in sequence to produce the study findings.

<The analytic code for Cohort 2 has been made available on GitHub. While the analysis code for Cohort 1 is fundamentally the same, it has not been uploaded due to data privacy policies>
