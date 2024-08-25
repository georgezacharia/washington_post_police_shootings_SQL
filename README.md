# 🛡️ Police Shootings Analysis

## Project Objective
The aim of this project is to conduct a thorough analysis of the Washington Post Police Shootings dataset from 2015-2024 using SQL within Jupyter Notebook. The goal is to uncover patterns and insights regarding the demographics of those involved, the circumstances of the shootings, and the use of body cameras. These insights are crucial for informing discussions on police practices and developing strategies to reduce such incidents.

## Data Source
The dataset used in this analysis is sourced from **[Kaggle](https://www.kaggle.com/)**, originally compiled by The Washington Post. It includes detailed records of police shootings across the United States.

## Tools & Technologies Used
- **SQL**: For querying and analyzing the data.
- **Jupyter Notebook**: Used as the interactive environment for running SQL queries.
- **Pandas**: For data manipulation and integration with SQL.
- **Seaborn & Matplotlib**: For creating visualizations and plots.

## Dataset Columns
- **`date`**: The date of the shooting (object).
- **`name`**: The name of the individual involved (object).
- **`age`**: The age of the individual (object).
- **`gender`**: The gender of the individual (object).
- **`armed`**: The type of weapon the individual was armed with, if any (object).
- **`race`**: The race of the individual (object).
- **`city`**: The city where the shooting occurred (object).
- **`state`**: The state where the shooting occurred (object).
- **`flee`**: Whether the individual attempted to flee, and by what means (object).
- **`body_camera`**: Whether the shooting was captured on a body camera (boolean).
- **`signs_of_mental_illness`**: Whether the individual showed signs of mental illness (boolean).
- **`police_departments_involved`**: The police department(s) involved (object).

## Analysis & Findings

### 1. 👮‍♂️ Distribution of Shootings by State
The data reveals that California (CA) tops the list with the highest number of police shootings, followed by Texas (TX) and Florida (FL). These states may require more focused interventions to understand and address the underlying causes.

### 2. 📊 Age Distribution of Individuals Involved in Shootings
Most individuals involved in shootings are between 20-39 years old, with the 30-39 age group being the most common. This suggests that young to middle-aged adults are more frequently involved in such incidents.

### 3. 🎥 Body Camera Usage in Police Shootings
The data shows that body cameras are not consistently used across all states. While California has the highest number of shootings, it also leads in the use of body cameras, though there is still significant room for improvement.

### 4. 🤯 Incidents Involving Signs of Mental Illness
Approximately 20% of the total shootings involved individuals showing signs of mental illness. This indicates a critical need for better mental health intervention strategies within law enforcement.

### 5. 🏙️ City-wise Analysis of Police Shootings
Los Angeles, Phoenix, and Houston are the cities with the highest number of police shootings. These cities may benefit from specific policies aimed at reducing these incidents.

### 6. 🔫 Analysis of Armed Status in Police Shootings
The majority of individuals involved in shootings were armed, with guns being the most common weapon. A significant number were unarmed or the armed status was undetermined, highlighting potential issues in threat assessment.

### 7. 🏳️ Analysis of Race in Police Shootings
White individuals account for the majority of those involved in shootings, followed by Black and Hispanic individuals. However, the data also shows a significant number of cases where race was recorded as unknown.

### 8. 🏃 Analysis of Fleeing Behavior in Police Shootings
Most individuals did not attempt to flee during the incidents. However, among those who did, fleeing by car and on foot were the most common methods.

### 9. 🚹 Analysis of Gender in Police Shootings
The vast majority of individuals involved in shootings were male. Female involvement was significantly lower, and there were very few cases with non-binary individuals.

## Recommendations
Based on the findings, the following recommendations are proposed:
1. **Enhanced Use of Body Cameras**: Increased deployment and consistent use of body cameras across all states could provide more transparency and accountability in police operations.
2. **Mental Health Training**: Law enforcement should receive better training to handle situations involving individuals with mental health issues.
3. **Community Engagement**: Cities with high numbers of shootings should engage with communities to build trust and develop non-lethal methods of conflict resolution.
4. **Threat Assessment Protocols**: Improved threat assessment protocols are needed to ensure that the use of force is proportionate and justified, especially in cases involving unarmed individuals.

## Conclusion
This analysis provides valuable insights into the patterns and factors involved in police shootings in the United States. By addressing the issues identified, law enforcement agencies can work towards reducing the frequency and severity of such incidents, ultimately leading to safer communities for everyone.

---

**Authored by:** George Zacharia
