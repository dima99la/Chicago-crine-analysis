# Chicago Crime Data Analysis

This project involves an in-depth analysis of crime data in Chicago from 2001 to 2022. The goal is to explore crime trends, identify patterns, and provide insights that could be useful for various stakeholders, such as law enforcement agencies, urban planners, and families looking for safe neighborhoods.

## Project Overview

The project analyzes a large dataset containing information about different types of crimes in Chicago. The analysis covers various dimensions such as time, location, and crime type, providing insights into:

- Trends in the overall crime rate from 2001 to 2022.
- Seasonal variations in crime rates.
- Crime distribution by time of day, day of the week, and month.
- Crime hotspots across different wards in Chicago.
- Probability of arrest depending on the type of crime and the time of day.

## Data Description

The dataset used for this analysis includes the following columns:

- `unique_key`: A unique identifier for each crime record.
- `case_number`: The case number associated with the crime.
- `date`: The date and time when the crime occurred.
- `block`: The block where the crime took place.
- `iucr`: The Illinois Uniform Crime Reporting code.
- `primary_type`: The primary classification of the crime.
- `description`: A detailed description of the crime.
- `location_description`: The type of location where the crime occurred.
- `arrest`: A boolean indicating whether an arrest was made.
- `domestic`: A boolean indicating whether the crime was domestic-related.
- `beat`, `district`, `ward`, `community_area`: Geographical identifiers for the location of the crime.
- `fbi_code`: The FBI classification code for the crime.
- `x_coordinate`, `y_coordinate`: The geographical coordinates of the crime location.
- `year`: The year when the crime occurred.
- `updated_on`: The timestamp when the record was last updated.
- `latitude`, `longitude`: The latitude and longitude of the crime location.
- `location`: A tuple containing the latitude and longitude.
- `row_num`: The row number in the dataset.

## Analysis and Visualization

### Key Insights

1. **Overall Crime Trends**: Crime rates in Chicago have generally been declining over the years, with significant drops observed in 2020 and 2021, likely due to the COVID-19 pandemic.

2. **Seasonal Patterns**: Crime rates tend to peak during the summer months (June, July, August) and decline during the winter months.

3. **Time of Day Analysis**: There are distinct patterns in crime rates depending on the time of day, with spikes in the early morning (6:00-9:00 AM) and around noon.

4. **Ward Analysis**: Certain wards, such as Ward 19, have shown consistent declines in crime rates, making them potentially safer areas for families.

5. **Crime Type Analysis**: Different types of crimes have different temporal patterns. For example, street crimes show significant seasonal variations, while residential crimes are more stable throughout the year.

### Visualizations

- **Crime Counts by Year**: Bar charts showing the number of crimes resulting in arrests versus no arrests, stacked by year.
- **Crime by Ward**: Line charts illustrating crime trends in different wards over time.
- **Crime by Month**: Scatter plots showing the number of crimes by month, distinguishing between arrests and non-arrests.
- **Crime by Hour**: Line charts showing the distribution of crimes throughout the day.
- **Heatmaps**: Visualizing the temporal patterns of different crime types.

## How to Use This Repository

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `sklearn`, `datetime`, `pytz`, `folium`

