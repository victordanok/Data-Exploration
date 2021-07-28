# INVESTIGATING A NO-SHOW HOSPITAL APPOINTMENT DATASET
## Overview
The relationship between the variables were explored in this project.

## Libraries Used
<ul>
  <li> Numpy </li>
  <li> Pandas </li>
  <li> matplotlib and Seaborn for visualizations </li> </ul>
  
## Data
The data is no-show hospital appointment

Data columns (total 14 columns):

1. PatientId
2. AppointmentID
3. Gender
4. ScheduledDay
5. AppointmentDay 
6. Age 
7. Neighbourhood 
8. Scholarship 
9. Hypertension
10. Diabetes 
11. Alcoholism 
12. Handcap
13. SMS_received 
14. No-show

<ul> 
  <li> The data has already been cleaned. Hence, there were no null values present in the dataset </li>
  <li> Feature engineering has already been done by encoding the categorical columns. </li> </ul>

## Feature Engineering
A new column <b> Agegroup </b> was created to easily categorize the continuous data in the age column.

## Conclusion
<ul>
  <li> From correlation among the variables, the highest gotten is 0.5 between hypertension and age, and the older one gets, the more likely it is to become hypertensive. </li>
  <li> Another correlation is between diabetes and hypertension 0.4, which indicates a diabetic patient is prone to hypertension. </li>
  <li> Most of the patients enrolled do not have an health scholarship </li>
  <li> The older patients have a higher risk of contracting diabetes, hypertension or alcoholism </li>
  <li> From the age group distribution chart, we see that the data is skewed towards the younger patients, this might suggest why we dont see higher cases of hypertension and diabetes amongst the dataset. </li>
  <li> Some of the patients under the age of , partake in the illegal consumption of alcohol and this behavior is more prone in males than females. </li>
  <li> The information gathered from the dataset shows that the SMS reminders do not play any significant role in getting a patient to keep their appointment as more turn outs were gotten from patients who didnt get any reminders </li>
    </ul>
