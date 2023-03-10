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

**Age** is correlated to hypertension and these two variables have an effect on whether a patient would show up for an appointment or not. The probability of a patient showing up increases with age.
SMS notification for the appointment is necessary for a patient to show up for an appointment.
Scholarship, diabetes, alcoholism, handicap, waiting days, gender, neighborhood, and scheduled day of the week do not seem to affect the decision of a patient in showing up or not.

**Limitations**<br/>
There were several limitations to this analysis, including:
Further investigation is required to understand why there is a higher proportion of females attending the hospital. It may be related to gynecological issues, but additional data is needed to determine the exact reasons.
Including features such as marital status and employment status in the dataset would provide more insights into the reasons for patients not showing up for appointments.
Expanding the dataset to include more countries or regions would enhance the generalizability of the findings.
The "no_show" column can be confusing as the values are reversed from what the column name suggests. This issue should be addressed in data processing and analysis.
There were some data entries where the waiting days were negative, indicating errors in data collection or input. This issue needs to be investigated and resolved.
The fact that some individuals with chronic diseases tend not to show up for appointments goes against common expectations. To understand the possible reasons for this, demographic information and additional data may need to be collected and analyzed.








**Conclusion**<br/>
Overall, this analysis identified age and hypertension as important factors for predicting whether a patient will show up for their appointment. It also emphasized the importance of SMS notification for appointment reminders. Further research can be conducted to identify other factors that affect patient attendance at medical appointments.
