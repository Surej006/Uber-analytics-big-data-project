# Uber Analytics Using PySpark

## Project Overview

This project analyzes Uber trip data using Apache Spark and PySpark to identify ride demand patterns and generate business insights. The dataset was processed using Spark's distributed computing framework, and the results were visualized using Plotly.

## Objectives

* Analyze Uber ride demand patterns
* Identify peak ride hours
* Determine the busiest days
* Perform monthly ride analysis
* Generate business insights from transportation data

## Technologies Used

* Python
* Apache Spark
* PySpark
* Pandas
* Plotly
* Google Colab

## Dataset

**Dataset:** Uber Trip Data (April 2014)

**Source:** FiveThirtyEight Uber TLC FOIL Dataset

The dataset contains Uber pickup records in New York City for April 2014.

### Columns Used

* **Date/Time** – Timestamp of the Uber pickup
* **Lat** – Pickup latitude
* **Lon** – Pickup longitude
* **Base** – Uber dispatch base code

The dataset was used to analyze ride demand patterns by extracting time-based features such as Hour, Day, and Month.

## Project Workflow

1. Load Uber trip data using PySpark
2. Explore and inspect the dataset
3. Convert Date/Time into Timestamp format
4. Extract Hour, Day, and Month features
5. Perform aggregations using groupBy() and count()
6. Analyze hourly, daily, and monthly ride demand
7. Convert Spark DataFrames to Pandas
8. Create interactive visualizations using Plotly
9. Generate business insights from the results

## Key Findings

* Peak ride demand occurred at **5 PM (Hour 17)**, indicating strong evening commuting activity.
* Uber demand followed a clear daily pattern, increasing throughout the day and peaking during evening hours.
* Ride volumes varied across different days of the month, showing fluctuations in customer demand.
* Early morning hours recorded lower ride activity compared to daytime and evening periods.

## Business Insights

The findings from this analysis can help transportation companies:

* Improve driver allocation during peak demand periods
* Support demand forecasting and operational planning
* Optimize surge pricing strategies
* Enhance resource utilization based on customer demand patterns

## Conclusion

This project demonstrates how Apache Spark and PySpark can be used to process and analyze large-scale transportation datasets efficiently. By extracting time-based features and performing aggregations, valuable insights into Uber ride demand patterns were identified and visualized.

## Future Enhancements

* Analyze multiple months of Uber trip data
* Perform geospatial analysis using pickup locations
* Build an interactive dashboard using Streamlit
* Apply Spark SQL for advanced analytics
* Create heatmaps and location-based demand visualizations
