# VISUAL-ANALYTICS
INTERNSHIP TASKS


 Dataset Information
The dashboard is built using the Heart Disease dataset containing patient medical information including:

- Age
- Gender
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG Results
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression (Oldpeak)


\\Dashboard Overview
The dashboard contains multiple visualizations that help analyze patient demographics and cardiovascular health.

1-\\Patients by Age
-Chart Type:Bar Chart
-Purpose:Displays the number of patients in each age group.
-Columns Used:age
-Metric:COUNT(*)
-Insight:
- Most patients belong to the age group between **50–60 years**.
- Very few patients are younger than 35 years.
- Heart disease is more common among middle-aged and older individuals.


2-\\Cholesterol Distribution
-Chart Type: Histogram
-Purpose:Shows the distribution of cholesterol levels among patients.
-Column Used: chol
-Insight:
- Majority of patients have cholesterol levels between **190–290 mg/dL**.
- A small number of patients have extremely high cholesterol.


3-\\Maximum Heart Rate Distribution
-Chart Type:Histogram
-Purpose:Shows how maximum heart rate varies among patients.
-Column Used:thalach
-Insight:
- Most patients achieved heart rates between **140–170 bpm**.
- Very high heart rates are relatively uncommon.


4-\\Chest Pain vs Gender
-Chart Type: Heat Map
-Columns Used:
- cp (Chest Pain Type)
- sex (Gender)
-Metric:COUNT(*)
-Purpose:Compares chest pain categories between male and female patients.
-Insight:
- Certain chest pain categories occur more frequently in males.
- The color intensity indicates the number of patients in each category.
- Darker colors represent fewer patients while lighter colors represent higher patient counts.


5-\\Cholesterol by Chest Pain Type
-Chart Type:Box Plot
-Columns Used:
- cp
- chol
-Purpose:Compares cholesterol levels across different chest pain categories.
-Insight:
- Each box represents the distribution of cholesterol.
- The center line represents the median cholesterol level.
- Individual points outside the whiskers represent outliers.


6-\\Average Heart Rate by Exercise-Induced Angina
-Chart Type:Bar Chart
-Columns Used:
- exang
- thalach
-Metric:AVG(thalach)
-Purpose:Compares average maximum heart rate between patients with and without exercise-induced angina.
-Insight:
- Patients without exercise-induced angina generally achieve a higher average heart rate.
- Patients experiencing angina tend to have a lower exercise heart rate.


7-\\Total Patients
-Chart Type: KPI Card
-Metric:COUNT(*)
-Purpose:Displays the total number of patient records available in the dataset.
-Dashboard Value:Provides an overall summary of the dataset size.


8-\\ Average Age
-Chart Type: KPI Card
-Metric:AVG(age)
-Purpose:Displays the average age of all patients.
 -Dashboard Value:Quickly summarizes the overall age profile of the patient population.


9-\\Average Cholesterol
-Chart Type: KPI Card
-Metric:AVG(chol)
-Purpose:Displays the average cholesterol level across all patients.
-Dashboard Value:Provides a quick overview of the population's cholesterol status.


10-\\ Chest Pain Type Distribution
-Chart Type:Treemap
-Column Used: cp
-Metric:COUNT(*)
-Purpose:Shows the proportion of patients belonging to each chest pain category.
-Insight:
- Larger rectangles represent more common chest pain types.
- Smaller rectangles indicate less frequent categories.



\\ Key Performance Indicators (KPIs)
The dashboard includes three KPI cards:
- Total Patients
- Average Age
- Average Cholesterol

