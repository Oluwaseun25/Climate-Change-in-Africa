# Climate Change in Africa: Temperature Analysis (1980-2023)

## Introduction

This project analyzes the historical temperature data for five African countries: Egypt, Tunisia, Cameroon, Senegal, and Angola. The dataset, provided by the U.S. Global Change Research Program, spans from 1980 to 2023 and includes daily minimum, maximum, and average temperatures. By leveraging data visualization techniques in Python, we aim to uncover insights and trends in temperature fluctuations over time.

## Dataset Description

The dataset contains the following columns:
- **Date**: The date of the temperature reading.
- **Country**: The country where the data was recorded (Egypt, Tunisia, Cameroon, Senegal, Angola).
- **Min_Temperature**: The minimum temperature recorded on that day (in degrees Celsius).
- **Max_Temperature**: The maximum temperature recorded on that day (in degrees Celsius).
- **Avg_Temperature**: The average temperature calculated from the daily min and max temperatures (in degrees Celsius).

## Project Goals

- Analyze temperature trends over time for each country.
- Visualize the seasonal variations and long-term trends.
- Compare temperature changes across the five countries.
- Identify any significant anomalies or patterns.

## Tools and Libraries

This project uses the following tools and libraries:
- **Python**: Programming language for data analysis and visualization.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: For statistical data visualization.

## Installation

To get started with the project, you'll need to have Python installed. You can then install the necessary libraries using pip:

```sh
pip install pandas matplotlib seaborn
```

## Usage

1. **Clone the repository:**

```sh
git clone https://github.com/Oluwaseun25/Climate-Change-in-Africa.git
cd Climate-Change-in-Africa
```

2. **Run the analysis script:**

The main analysis and visualization are contained in the `Africa Climate.py` script. You can run this script to generate the visualizations:

```sh
python Africa Climate.py
```

## Data Analysis and Visualization

### Temperature Trends Over Time

We analyze how the minimum, maximum, and average temperatures have changed from 1980 to 2023 for each country. The following plots are generated:
- **Line plots** showing the temperature trends over the years.
- **Box plots** for visualizing the distribution of temperatures over different decades.

### Comparative Analysis

We compare the temperature trends across the five countries to identify any common patterns or unique changes. The following visualizations are included:
- **Overlayed line plots** for direct comparison.
- **Bar charts** showing the average temperature changes per decade for each country.

### Seasonal Variations

We investigate the seasonal patterns in temperature for each country:
- **Monthly temperature trends** displayed using line plots.
- **Seasonal decomposition** to highlight trends, seasonality, and residuals.

## Results

The visualizations reveal several key insights:
- **Increasing temperature trends**: All five countries show an upward trend in average temperatures over the decades.
- **Seasonal patterns**: Distinct seasonal variations are observed, with certain months consistently showing higher or lower temperatures.
- **Comparative differences**: While all countries are warming, the rate and extent of warming differ, highlighting regional climate variations.

## Conclusion

This project provides a comprehensive analysis of temperature changes in five African countries over the past four decades. The insights gained from this analysis can inform further research on climate change impacts and adaptation strategies in the region.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests with improvements or additional analyses.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

We thank the U.S. Global Change Research Program for providing the dataset and the open-source community for the tools and libraries used in this project.