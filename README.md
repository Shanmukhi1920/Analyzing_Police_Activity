
# Analyzing Police Activity with Python

## Project Overview
This project delves into a dataset of traffic stops by police officers, collected by the Stanford Open Policing Project, focusing specifically on data from Rhode Island. The analysis seeks to uncover insights into police activity, examining the impact of driver gender and weather conditions on police behavior.

## Datasets
- `police.csv`: Detailed records of traffic stops, including driver demographics, violations, searches, and stop outcomes.
- `weather.csv`: Daily weather conditions from a weather station near Rhode Island's center, providing context for the environmental conditions during traffic stops.

## Methodology
1. **Data Preparation and Cleaning**: Addressed missing values, dropped irrelevant columns, and transformed data types for more accurate analysis.
2. **Gender and Policing**: Investigated the relationship between driver gender and traffic violations, finding differences in violation types and search rates between genders.
3. **Impact of Time and Drugs**: Analyzed the arrest rate over different times of the day and the trend in drug-related stops over the years.
4. **Weather Conditions and Policing**: Explored how weather conditions affect the rate of arrests and policing behavior.

## Requirements
- Python 3.x
- Libraries: pandas, NumPy, Matplotlib, seaborn

## Installation and Usage
```bash
git clone https://github.com/Shanmukhi1920/Analyzing_Police_Activity
cd Analyzing_Police_Activity
jupyter notebook
```
Then, open `Analyzing_Police_Activity.ipynb` in Jupyter.

## Results
- **Gender and Violations**: Females are more often stopped for speeding, whereas males have a more varied distribution of violations.
- **Gender and Search Rates**: Males are searched more than twice as often as females, across all types of violations.
- **Time and Arrest Rate**: A significant spike in arrest rates is observed overnight, with a dip in the early morning hours.
- **Drug-Related Stops**: An increase in drug-related stops over 10 years, despite a decrease in search rates.
- **Weather Impact**: Arrest rates increase as the weather worsens, a trend that persists across various violation types.

