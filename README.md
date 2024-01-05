
# Delhi Weather Analysis and Forecasting

## Introduction

This project focuses on the analysis and forecasting of weather conditions in Delhi, India. Using historical weather data, this project aims to provide insights into temperature, humidity, and wind speed trends over the years in Delhi. Additionally, it employs the Facebook Prophet model for future weather forecasting.

## Data Source

The dataset used in this project is "DailyDelhiClimateTrain.csv", which includes daily weather measurements such as mean temperature, humidity, and wind speed in Delhi.

## Features

- Data Analysis of weather conditions (mean temperature, humidity, and wind speed).
- Visualization of weather trends over time.
- Analysis of the relationship between temperature and humidity.
- Monthly and yearly trends in temperature changes.
- Weather forecasting using the Facebook Prophet model.

## Tools and Libraries

The project uses Python and several libraries for data manipulation, analysis, and visualization:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Prophet (for forecasting)

## Getting Started

To run this project, you need to have Python installed on your system along with the above-mentioned libraries. The main dependencies can be installed using:

```
pip install pandas numpy matplotlib seaborn plotly prophet
```

## Usage

1. **Data Analysis and Visualization:**
   - The script includes commands for loading the data, generating basic statistics, and information about the dataset.
   - It also contains lines for creating various plots (line and scatter plots) to analyze weather trends.

2. **Temperature Change Analysis:**
   - The date column is converted to datetime format.
   - New columns for year and month are added for more detailed analysis.
   - A line plot is generated to visualize temperature changes over the years.

3. **Weather Forecasting:**
   - The dataset is prepared for forecasting by renaming columns to fit Prophet model requirements.
   - The Prophet model is then used to forecast future weather conditions.

## Example Plots and Forecasts

*Include some screenshots of your plots and forecasts here.*

## Contributing

Contributions to the project are welcome. You can contribute in several ways:
- Improving the forecasting model.
- Extending the analysis to include other weather parameters.
- Optimizing the code for better performance.

## License

*Include details about the license here, if applicable.*

