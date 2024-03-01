# Household Electric Power Consumption Patterns
Energy data exploration through Machine Learning models

![image](https://github.com/gyaneshpandey09/energy/assets/13755458/869dbe2e-a82f-4a97-abce-23f3c4020038)

| Datetime            | Global_active_power | Global_reactive_power | Voltage | Global_intensity | Sub_metering_1 | Sub_metering_2 | Sub_metering_3 |
|---------------------|---------------------|-----------------------|---------|------------------|----------------|----------------|----------------|
| 2006-12-16 17:24:00 | 4.216               | 0.418                 | 234.840 | 18.400           | 0.000          | 1.000          | 17.0           |
| 2006-12-16 17:25:00 | 5.360               | 0.436                 | 233.630 | 23.000           | 0.000          | 1.000          | 16.0           |
| 2006-12-16 17:26:00 | 5.374               | 0.498                 | 233.290 | 23.000           | 0.000          | 2.000          | 17.0           |
| 2006-12-16 17:27:00 | 5.388               | 0.502                 | 233.740 | 23.000           | 0.000          | 1.000          | 17.0           |
| 2006-12-16 17:28:00 | 3.666               | 0.528                 | 235.680 | 15.800           | 0.000          | 1.000          | 17.0           |

## Plotting Global Active Power
![image](https://github.com/gyaneshpandey09/energy/assets/13755458/175011b5-2c0d-4d1d-b8a4-5d027952efd4)

## Feature Importance from Model
### RandomForestRegressor
| Feature               | Value    |
|-----------------------|----------|
| Global_intensity      | 0.998186 |
| Voltage               | 0.000740 |
| Global_reactive_power | 0.000550 |
| Sub_metering_1        | 0.000242 |
| Sub_metering_3        | 0.000171 |
| Sub_metering_2        | 0.000112 |


## Clustering Analysis
![image](https://github.com/gyaneshpandey09/energy/assets/13755458/d38fd690-8a4b-4d2b-8fb6-bf3f452bf094)

![image](https://github.com/gyaneshpandey09/energy/assets/13755458/300a4409-9168-4540-9801-675ff8d29cfb)

## Note:
The dataset checkinto the repository is a small subset of the original dataset. Had to be truncated due to the size limitations at github.
Original Dataset: https://www.kaggle.com/datasets/uciml/electric-power-consumption-data-set?resource=download. 
 
