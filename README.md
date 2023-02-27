# COVID19_DA_Batch1
Analyzing covid_19 dataset

# Intro:
we made this project  as apart of training Data analysis using python  in Aiapproach club.

# Objective
the objective of our analyzing the dataset of COVID-19 patients is to  provide valuable insights into various aspects of the disease and to understanding disease we can identify factors that contribute to the disease's transmission, such as age, gender...,and the category concerned with this disease soTo confront the Coronavirus (COVID-19) pandemic, we need to understand the nature of this pandemic, and analyze the relevant data. There are many approaches in which these perceptions can lead to misleading conclusions. Therefore, creating good results comes with multiple challenges.
In this project, we discuss the analysis and interpretation of data,  by reviewing different types of results.

# About the dataset
The data obtained is from the Mexican government and hence, the analysis is valid for Mexico or maybe North America. The pandemic stats and behaviours are extremely different for Asian countries when compared to North American or European countries owing to far lower case fatality rate for Asia.
**Data Dictionary:**
1-id: The identification number of the patient
.
2-sex: Identify gender of the patient, 1 as female and 2 as male.
3-patient_type: Type of patient, 1 for not hospitalized and 2 for hosptalized.
4-entry_date: The date that the patient went to the hospital.
5-date_symptoms: The date that the patient started to show symptoms.
6-date_died: The date that the patient died, “9999-99-99” stands for recovered.
7-intubed: Intubation is a procedure that’s used when you can’t breathe on your own. Your doctor puts a tube down your throat and into your windpipe to make it easier to get air into and out of your lungs. A machine called a ventilator pumps in air with extra oxygen. Then it helps you breathe out air that’s full of carbon dioxide (CO2). “1” denotes that the patient used ventilator and “2” denotes that the patient did not, “97” “98” “99” means not specified.
8-pneumonia: Indicates whether the patient already have air sacs inflammation or not “1” for yes, “2” for no, “97” “98” “99” means not specified.
9-age: Specifies the age of the patient.
10-pregnancy: Indicates whether the patient is pregnant or not, “1” for yes, “2” for no, “97” “98” “99” means not specified.
11-diabetes: Indicates whether the patient has diabetes or not, “1” for yes, “2” for no, “97” “98” “99” means not specified.
12-copd: Indicates whether the patient has Chronic obstructive pulmonary disease (COPD) or not, “1” for yes, “2” for no, “97” “98” “99” means not specified.
13-asthma: Indiactes whether the patient has asthma or not, “1” for yes, “2” for no, “97” “98” “99” means not specified.
14-inmsupr: Indicates whether the patient is immunosuppressed or not, “1” for yes, “2” for no, “97” “98” “99” means not specified.
15-hypertension: Indicates whether the patient has hypertension or not, “1” for yes, “2” for no, “97” “98” “99” means not specified.
16-other_disease: Indicates whether the patient has other disease or not, “1” for yes, “2” for no, “97” “98” “99” means not specified.
17-cardiovascular: Indicates whether if the patient has heart or blood vessels realted disease, “1” for yes, “2” for no, “97” “98” “99” means not specified.
18-obesity: Indicates whether the patient is obese or not, “1” for yes, “2” for no, “97” “98” “99” means not specified.
19-renal_chronic: Indicates whether the patient has chronic renal disease or not, “1” for yes, “2” for no, “97” “98” “99” means not specified.
20-tobacco: Indicates whether if the patient is a tobacco user, “1” for yes, “2” for no, “97” “98” “99” means not specified.
21-contact_other_covid: Indicates whether if the patient has contacted another covid19 patient.
22-icu: Indicates whether the if the patient had been admitted to an Intensive Care Unit (ICU), “1” for yes, “2” for no, “97” “98” “99” means not specified.
23-covid_res: 1 indicates person is covid +ve,2 indicates person is covide -ve,3 indicates result is in awaiting process

# Steps :

1- Import libraries 
2- Upload and read the dataset 
3- Get some information about our dataset
4- study each column.
5- comparison between columns 
6- plotting clear graghs as much we need to explain the data and relations as much as we can.
7- clean the data and showing that by plotting graphs.
8- Data Visualization.
    finally plot covid_res column with other columns one by one and also study the relation between age and patients who have positive results.

# Conclusion of project:
Data analysis is a successful scientific method to capture disease information, and one of the things that is noticed after analyzing the data is that whoever was infected with the Corona virus will die, but we found through the analysis that a large percentage of the infected had recovered.
The data for Covid patients is very important to know the causes of the disease and who is most vulnerable to it among the groups of society. Through this data and analyzing it after cleaning it, we can train Moodle with very pure data.






