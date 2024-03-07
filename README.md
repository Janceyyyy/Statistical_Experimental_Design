# MacBook Battery Consumption Analysis

## Introduction

This project explores factors affecting MacBook battery consumption, motivated by the observation that MacBooks frequently run low on battery, causing inconvenience for college students. We focused on three potential factors: Brightness, Bluetooth, and Application operation.

## Experiment Design

We utilized a 2^3 factorial experiment design to examine the effects of Brightness, Bluetooth, and Application operation (all with two levels: low and high) on MacBook battery consumption, along with their second-order and third-order interactions.

### Technologies Used:

- **Statistical Analysis**: R-studio
- **Statistical Analysis**: Performed using ANOVA to understand the impact of each factor on battery consumption.
- **Data Visualization**: Utilized `ggplot2` from R for graphical representation of the data.
- **Programming Languages**: The experiment was analyzed using R, leveraging libraries such as `dplyr` for data manipulation and `readr` for data reading.

## Implementation

The experiment was conducted on a MacBook Air (13-inch, 2017), measuring the percentage of battery consumption under different conditions over 10 minutes. We repeated this process for all combinations of the three factors, conducting four replications for each to ensure reliability.

## Results

- **Significant Factors**: Bluetooth and Application operation were found to significantly affect battery consumption.
- **Brightness**: Its impact was not statistically significant, contrary to popular belief.
- **Interactions**: No significant interaction effects were observed between the factors.

## Conclusion

Our findings suggest that turning off Bluetooth and high-energy applications can significantly reduce battery consumption, more so than adjusting brightness.

## Future Work

Suggestions include expanding the factorial design for more detailed analysis and conducting the experiment on various MacBook models to generalize findings.

