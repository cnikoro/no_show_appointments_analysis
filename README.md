### Dataset Description
We are analyzing the no show appointments dataset originally sourced from Kaggle. This dataset contains medical information from about 100k medical appointments in Brazil. The names of the columns in this dataset are PatientId, AppointmentID, Gender, ScheduledDay, AppointmentDay, Age, Neighbourhood, Scholarship, Hipertension, Diabetes, Alcoholism, Handcap, SMS_received, and No-show.

The No-show column is the dependent variable. It comprises two values: "Yes" for patients that didn't show up for their appointment and "No" for those that showed up. The other columns are independent variables most of which are binary with two possible values. The ScheduledDay column is the date an appointment was scheduled, and the AppointmentDay column is the date for an appointment.

Our main goal is to determine possible factors that contribute to patients not showing up for their appointments.

### Question(s) for Analysis
To do this, we will be exploring the following questions:

* Are patients less likely to show up if they made several appointments?
* Are patients less likely to show up if they don't suffer from any of the following cases: hypertension, diabetes, alcohol related problems, or a disability?
* Are patients less likely to show up if they have a scholarship and suffer from any of the following cases: hypertension, diabetes, alcohol related problems, or a disability?
* Are patients less likely to show up if they receive an SMS?
* Are male patients less likely to show up than female patients?
* Are patients less likely to show up if their appointment is on the same day it was scheduled?
* Which of the age groups are less likely to show up?

### Conclusions
Here is a summary of our findings:

* patients with multiple appointments are probably less likely to show up than those with a single appointment;
* patients that don't suffer from any of the cases considered are probably less likely to show up for their appointments;
* patients are probably more likely to show up if they suffer from any of the health conditions but have a scholarship;
* we can't conclude that patients that didn't receive an SMS are less likely to show up compared to those that did because this only happened in the month of May;
* male patients are probably less likely to show up;
* patients are probably more likely to show up if their appointment fell on the same they that it was scheduled; and
* children are probably less likely to make their appointments while older adults are more likely to make theirs.

Therefore, the following factors might help us predict if a patient will likely not show up for their appointment:

* if they have more than one appointment
* if they don't suffer from any case of hypertension, diabetes, alcohol related problems or disability;
* if they don't have a scholarship;
* if they are males;
* if their appointments don't fall on the same day it is scheduled; and
* if they are children;

The above findings are not conclusive and would still need to undergo statistical tests.

### Limitations
We would need to research further on why there are patients with multiple appointments. We are not sure if the appointments were made with more than one health practitioners or if they were appointments that were rescheduled. Furthermore, it is possible that patients may suffer from other health problems that might determine if they will or will not show up for their appointments which were not recorded in the data set. This is another area that requires further research.
