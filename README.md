# Motor-Vehicle-Theft-Analysis
This project focused on analyzing motor vehicle theft (MVT) data from Phoenix for the months of November and December in 2015 and 2016. By identifying high-risk timeframes, locations, and premise types, the study aimed to uncover patterns in theft activity that could inform smarter law enforcement strategies and community safety efforts.

## Introduction
Motor vehicle theft remains a major urban crime concern, and understanding the “when” and “where” behind these incidents is essential. This project aimed to break down historical theft data to highlight temporal and spatial trends, using publicly available datasets from the city of Phoenix.

## Objective
* Detect changes in MVT trends between 2015 and 2016
* Identify the timeframes and premises where thefts most frequently occur
* Determine ZIP codes with the highest concentration of vehicle theft incidents
* Provide actionable insights for crime prevention and law enforcement resource allocation

## Dataset 
The dataset was sourced from Kaggle’s Motor Vehicle Theft dataset for the city of Phoenix, covering incidents from November and December of 2015 and 2016. It includes fields such as Time_Occurred, Time_Frame, ZIP, and Premise_Type. Python (Pandas, NumPy, and Datetime) was used for data cleaning and transformation, while visualizations were created using Matplotlib and Seaborn to explore geographic and temporal trends.

## Python Libraries Used
* Pandas – for data cleaning, grouping, and aggregating theft data by time, location, and premise type
* Matplotlib and Seaborn – to visualize trends and comparisons across years, ZIP codes, and timeframes
* NumPy – to support numerical operations and array-based transformations
* Datetime – to categorize and parse time-related fields like Time_Occurred and Time_Frame

## Conclusion
The analysis revealed that thefts were most frequent during evening hours, with specific ZIP codes and residential premises disproportionately affected. The number of thefts slightly increased in 2016 compared to 2015. These insights enable law enforcement agencies to focus surveillance efforts during peak hours in high-theft zones, and also raise awareness among residents to improve vehicle safety.
