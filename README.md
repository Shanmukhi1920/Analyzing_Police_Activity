

## Overview
This project analyzes a dataset of police traffic stops in Rhode Island, sourced from the Stanford Open Policing Project. The study aims to uncover patterns in police activity, with a particular focus on how driver gender and weather conditions influence police behavior during traffic stops. By examining these factors, the project seeks to provide insights into potential biases or trends in law enforcement practices. The findings may be valuable for law enforcement agencies, policymakers, and researchers studying racial and gender disparities in policing, as well as the impact of external factors like weather on police decision-making during traffic stops.

## Datasets
- `data/police.csv`: Detailed records of traffic stops, including driver demographics, violations, searches, and stop outcomes.
- `data/weather.csv`: Daily weather conditions from a weather station near Rhode Island's center, providing context for the environmental conditions during traffic stops.

## Methodology
1. **Data Preparation and Cleaning**: Addressed missing values, dropped irrelevant columns, and transformed data types for more accurate analysis.
2. **Gender and Policing**: Investigated the relationship between driver gender and traffic violations, finding differences in violation types and search rates between genders.
3. **Impact of Time and Drugs**: Analyzed the arrest rate over different times of the day and the trend in drug-related stops over the years.
4. **Weather Conditions and Policing**: Explored how weather conditions affect the rate of arrests and policing behavior.


## Installation and Usage
```bash
git clone https://github.com/Shanmukhi1920/Analyzing_Police_Activity
cd Analyzing_Police_Activity
pip install -r requirements.txt
jupyter notebook
```
Then, open `Analyzing_Police_Activity.ipynb` present in the `notebooks/` directory in Jupyter.

## Results
- **Gender and Violations**: Females are more often stopped for speeding, whereas males have a more varied distribution of violations.
- **Gender and Search Rates**: Males are searched more than twice as often as females, across all types of violations.
- **Time and Arrest Rate**: A significant spike in arrest rates is observed overnight, with a dip in the early morning hours.
- **Drug-Related Stops**: An increase in drug-related stops over 10 years, despite a decrease in search rates.
- **Weather Impact**: Arrest rates increase as the weather worsens, a trend that persists across various violation types.

