# Analyzing_Police_Activity

## Context

Explore the Stanford Open Policing Project dataset and analyze the impact of gender and weather effects on police behavior.

## Methodology
1. Data Loading:

  - The police and weather data were imported and examined to understand their structure and contents.
  - Rows with a small fraction of missing values were dropped to ensure data integrity.
  - Data types were adjusted as necessary, and a datetime index was created to facilitate time-based analysis.
2. Exploratory Data Analysis (EDA):

  - The relationship between gender and policing was explored, examining factors such as arrest rates, drug rates, and violations across different genders.
  - Visualizations were created to represent the distribution of arrests, drug-related incidents, and violations across various police districts.
  - The impact of weather conditions on policing activities was analyzed, investigating how weather variables influence law enforcement actions.
  - Both the police and weather datasets were integrated to gain insights into the relationship between weather conditions and arrest rates.
    
## Insights
Based on the analysis conducted on the police and weather data, the following are the key findings and insights:

1. Speeding violations are the most common, followed by other moving violations and equipment violations.
2. About two-thirds of female traffic stops are for speeding, while male stops are more evenly distributed among violation categories.
3. The high proportion of female stops for speeding does not necessarily mean that females speed more than males, as the analysis did not consider the number of stops or drivers.
4. Approximately 95% of stops for speeding result in a ticket, indicating that gender does not significantly impact who receives a ticket for speeding.
5. Male drivers are searched more than twice as often as female drivers, suggesting the presence of another factor influencing search rates.
6. Hypotheses regarding search rates varying by violation type were disproven, as the search rate for males remained higher across all violation categories.
7. Protective frisks were conducted 164 times, with a higher rate for males, although the analysis couldn't conclude that gender alone caused the difference.
8. The arrest rate shows a significant spike overnight and dips in the early morning hours, indicating potential patterns in police behavior.
9. The rate of drug-related stops nearly doubled over a 10-year period, which cannot solely be attributed to an increase in vehicle searches.
10. Different police zones exhibit distinct patterns, with Zone K1 having a majority of stops for speeding and Zones K2 and K3 showing similar violation distributions.
11. Stops for warrant and call for service have longer average stop times, exceeding 20 minutes.
12. Analysis of weather data suggests a potential correlation between worse weather conditions and increased arrest rates across various violation types.
 
