# README for Steel Industry Energy Consumption Dataset

## Overview

This repository contains the Steel Industry Energy Consumption Dataset, which includes detailed records of energy usage and related metrics from various steel manufacturing facilities. The dataset is designed to support research, analysis, and optimization efforts in energy management and environmental impact studies within the steel sector.

## Dataset Description

- **Total Entries**: 35,040
- **Total Columns**: 11

### Columns

1. **date**: The date of the recorded data point.
2. **Usage_kWh**: Total energy consumption in kilowatt-hours.
3. **Lagging_Current_Reactive.Power_kVarh**: Reactive power consumption (kVarh) for lagging current conditions.
4. **Leading_Current_Reactive_Power_kVarh**: Reactive power consumption (kVarh) for leading current conditions.
5. **CO2(tCO2)**: Carbon dioxide emissions in tons.
6. **Lagging_Current_Power_Factor**: Power factor for lagging current conditions.
7. **Leading_Current_Power_Factor**: Power factor for leading current conditions.
8. **NSM**: Numerical identifier for the steel manufacturing facility.
9. **WeekStatus**: Categorical status indicating whether the date is a weekday or weekend.
10. **Day_of_week**: The day of the week corresponding to each date entry.
11. **Load_Type**: Classification of the load type (e.g., base load, peak load).

## Usage

The dataset can be used for various analyses, including:

- Energy consumption trend analysis
- Environmental impact assessments related to CO2 emissions
- Operational efficiency optimization
- Predictive modeling of energy consumption patterns

## Data Collection

The data was collected from multiple steel manufacturing plants over a continuous period using the following methods:

- **Automated Data Logging**: Energy meters captured real-time data.
- **Periodic Sampling**: Daily aggregation of data points to maintain consistency.
- **Standardization**: All measurements were standardized for comparability.

## Requirements

To analyze the dataset, you may need the following tools and libraries:

- Python (version 3.6 or later)
- Pandas
- Matplotlib / Seaborn (for data visualization)

## Example Code

Here is a basic example of how to load and explore the dataset using Python:

```python
import pandas as pd

# Load the dataset
df = pd.read_csv('steel_industry_energy_consumption.csv')

# Display the first few rows
print(df.head())

# Summary statistics
print(df.describe())
```

## License

This dataset is provided for educational and research purposes. Please cite the source if you use this data in your work.

## Contact

For any questions or feedback regarding this dataset, please contact at creaters645@gmail.com.
