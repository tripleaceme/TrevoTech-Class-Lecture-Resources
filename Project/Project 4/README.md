# Medical Appointments Analysis Project
This is the 4th project in the Trevotech Data Analysis Class

## Dataset

This dataset collects information from more than 100k medical appointments in Brazil and is focused on wether or not patients show up for their medical appointments. 
The analysis will be based on analyzing the different reasons that could have influenced the patients to show up for their appointment or not show up. The data features
incude PatientId, AppointmentID, Gender, ScheduledDay, AppointmentDay, Age, SMS_received and some other additional variables. The dataset can be downloaded from 
[here](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv)


## Summary of Findings

In this analysis, I found out that patients who have closer appointment dates showed up for their appointments, unlike patients whose appointments dates are father in the 
calendar. Patients whose appointment dates fell in during the weekdays like Monday to Thursaday showed up for their appointments than patients who had appointments during
the weekends. 

Also, receiving an sms reminder before the appointment dates did not make the patients to show up for their appointments because the patients who didn't recieve an sms 
showed up more than the people who recieved sms reminder for their appointments.

I also found out that patients who are suffering from acute diseases like Diabetes and Hyperstension showed up for their appointments more than the patients who 
weren't suffering from these diseases.

Patients who benefitted from the welfare scolarship scheme in Brazil showed up less than the patients who didn't have this scholarship.

From the analysis, I found that males and females have the same percentage of showing up or not showing up for their appointments.


## Key Insights for Presentation

For the presentation, I focused on showing the relationships between Independent variables (Gender, sms recieved, scholarship, Diabetes, appointment dates, and appointment
day names) and the dependent variable (showed).

I used countplot to introduce each of these independent variables one by one , and then went ahead to further show how they are connected 
to patients showing up for their appointments using countplots too.

I also used color palletes to seperate the indepent and dependent variables. This is to show the difference between the plots.

## Blog Post

[On LinkedIn](#)
