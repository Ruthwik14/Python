# Patient Appointment Analysis

## Introduction
This dataset compiles data from 100,000 medical appointments in Brazil, focusing on whether patients attend their appointments. With approximately 30% of patients missing their scheduled appointments, the central question revolves around understanding why. The aim is to identify key factors that influence patient attendance.

## Exploring the Data
### Questions to Explore:
1. **Gender Influence:** Is there a correlation between a patient's gender and their attendance?
2. **Neighborhood Impact:** Does the location of the hospital (neighborhood) affect patient attendance?
3. **Age Patterns:** Do older patients tend to prioritize their health and attend appointments more frequently than younger ones?
4. **Disease Effect:** How does the type of disease (e.g., hypertension, diabetes) impact patient attendance?

### Data Overview:
- **Dataset:** Patient Appointment No Show Factors_EDA_Analysis.csv
- **Columns:** Gender, ScheduledDay, AppointmentDay, Age, Neighbourhood, Scholarship, Hypertension, Diabetes, Alcoholism, Handicap, SMS_received, No-show
- **Summary Statistics:**
  - Total Entries: 110,527
  - Data Types: Float (1), Integer (8), Object (5)
- **No Missing Values or Duplicates**
- **Summary Statistics:** Provides insights into the distribution of numeric variables such as Age, Hypertension, and Diabetes.

## Data Analysis
1. **Gender vs. Attendance:** Visual analysis indicates that a higher proportion of females tend to show up for appointments compared to males. Further investigation into the reasons behind this discrepancy is warranted.
2. **Neighborhood Analysis:** There is variation in attendance rates across different neighborhoods, suggesting that the location of the hospital may influence patient behavior. This could be due to factors such as accessibility or healthcare infrastructure.
3. **Age vs. Attendance:** Contrary to initial assumptions, younger patients exhibit higher attendance rates compared to older patients. This challenges the conventional notion that older individuals prioritize their health more.
4. **Disease Impact:** Analysis reveals that patients with hypertension tend to show up for appointments regardless of their infection status. This underscores the potential influence of certain medical conditions on attendance behavior.

## Conclusion
- **Gender and Age:** Females and younger patients show higher attendance rates, highlighting potential demographic trends in healthcare utilization.
- **Neighborhood Dynamics:** The neighborhood of the hospital may play a role in patient attendance, suggesting the need for targeted interventions in specific areas.
- **Disease Considerations:** Certain medical conditions, such as hypertension, may serve as motivators for patients to attend appointments consistently, irrespective of other factors.

## Further Exploration
- Additional analysis is required to delve deeper into the underlying factors influencing patient attendance.
- Exploring patient demographics, socioeconomic status, and appointment scheduling practices could provide valuable insights into attendance behavior.
