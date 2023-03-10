# Medical-Appointments-No-Shows-Exploration

**Introduction**<br/>
This dataset contains information from 110k medical appointments in Brazil and focuses on the question of whether or not patients show up for their appointments. The dataset includes a variety of characteristics about the patient such as scheduled day, hospital location, scholarship status, and possible diseases like hypertension, diabetes, alcoholism, and handicap. The dependent variable is whether the patient showed up for the appointment or not.

**Analysis Goal**<br/>
The goal of this analysis is to identify factors that are important for predicting whether a patient will show up for their scheduled appointment.

**Dataset Source**<br/>
The original dataset was sourced from Kaggle Dataset: Medical Appointment No Shows on 29th October 2018.

**Tech Stack**<br/>
This analysis was performed using Python and the following libraries: Pandas, Numpy, Seaborn, and Matplotlib.

**Analysis Result**<br/>
The analysis was performed using both univariate and bivariate analysis involving distribution plots using proportions due to the imbalance of the dataset. The following findings were identified:

**Age is correlated to hypertension and these two variables have an effect on whether a patient would show up for an appointment or not. The probability of a patient showing up increases with age.
SMS notification for the appointment is necessary for a patient to show up for an appointment.
Scholarship, diabetes, alcoholism, handicap, waiting days, gender, neighborhood, and scheduled day of the week do not seem to affect the decision of a patient in showing up or not.

**Limitations**<br/>
There were several limitations to this analysis, including:

Invalid entries in the dataset such as appointments scheduled for past dates and about 1.3k duplicated entries were discovered and removed from the dataset. This reduced the volume of data used for analysis and could make the analysis result inaccurate.
The imbalance of the dataset might have resulted from the fact that the data available is only recorded for some occurrences in a year, limiting the understanding of the patients better.
There might be many other factors that can affect individual's decision to show up for an appointment or not, which are not covered in the dataset.

**Conclusion**<br/>
Overall, this analysis identified age and hypertension as important factors for predicting whether a patient will show up for their appointment. It also emphasized the importance of SMS notification for appointment reminders. Further research can be conducted to identify other factors that affect patient attendance at medical appointments.
