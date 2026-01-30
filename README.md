# Smartphone Battery Consumption Data

This repository contains a dataset for modeling smartphone battery consumption over a period of 72 hours (3 days). The data is sampled every 20 minutes and includes information on power usage based on user activity such as screen brightness, app usage, and network activity.

## Dataset Description

The dataset is divided into three CSV files, each representing one day of data. The columns in the dataset are as follows:

- **Time (minutes)**: Time in minutes, from 0 to 4320 minutes (72 hours).
- **Screen Brightness**: Simulated screen brightness level (ranging from 0 to 1).
- **App Usage**: Simulated app usage level (ranging from 0 to 1).
- **Network Activity**: Simulated network activity level (ranging from 0 to 1).
- **Power (W)**: The total power consumption at each time point, calculated based on the activity levels.
- **SOC**: State of Charge (SOC), representing the battery level, calculated based on the power consumption over time.

### Files

- **day1_battery_usage_data.csv**: Data for the first day (00:00 - 23:59).
- **day2_battery_usage_data.csv**: Data for the second day (00:00 - 23:59).
- **day3_battery_usage_data.csv**: Data for the third day (00:00 - 23:59).

## Usage

This dataset is intended for validating models related to smartphone battery life prediction, energy consumption analysis, and other related research.

You can download the CSV files and use them in your battery consumption models or for analysis.

## License

This dataset is provided for research and educational purposes. You are free to use, modify, and share the data, but please credit this repository if you use it in any projects or publications.

## Acknowledgements

The data in this repository was generated based on a set of assumptions about typical smartphone usage patterns. It is intended for validation of battery consumption models and may not fully represent real-world data.

## Contact

If you have any questions or need further information, feel free to open an issue or contact the repository owner.
