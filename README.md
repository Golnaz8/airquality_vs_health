# airquality_vs_health
Air quality impact on mortality rate

## Overview

The goal of the project is to evaluate how seven keys air pollutants—PM2.5, PM10, NO2, O3, SO2, CO, and NH3—affect mortality rates. These includes investigating whether higher levels of these pollutants correlate with increased mortality, using air pollution data and mortality statistics across different countries.

Data is collected from national sources(details in Data Resources) focusing on both pollutant levels and corresponding mortality rates. After cleaning the data, a correlation analysis will explore the relationship between pollution and mortality, with the results presented through graphs and maps to highlight any significant trends.

In conclusion, although CO may have the highest pollutant levels, PM10 and PM2.5 show the strongest correlations with increased mortality rates. Additionally, other factors, such as hygiene, also play a significant role in influencing mortality, complicating the relationship between pollution levels and health outcomes. These findings suggest that while air pollution is a key factor, broader environmental and public health conditions must be considered when addressing mortality risks.

## Table of Contents

- [Data Resources](#data-resources)
- [Usage Guide](#usage-guide)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Credits](#credits)
- [License](#license)

## Data Resources

- **OpenWeather API**: For real-time or historical air pollution data, providing pollutant concentrations (PM2.5, PM10, NO2, O3, SO2, CO, NH3).
- **World Health Organization (WHO) API**: For country-specific or regional mortality rates.
- **World Bank API**: For basic sanitation services for selected countries.

## Usage Guide

### 1. Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Golnaz8/airquality_vs_health.git
   cd airquality_vs_health

2. **Create virtual environment**:
    ```bash
    python -m venv env
    source env/bin/activate 

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt

### 2. API Key Setup

You will need to have API key for OpenWeatherMap to gather real-time data. Make sure to store these API keys in a .env file or as environment variables.
    
    weather_api_key=your_openweather_key

### 3. Running the Analysis

Start Jupyter Notebook:
    
    jupyter notebook


Open the notebook file and run the cells step by step to explore the data, visualize air quality impacts, and analyze the results.



## Screenshots
File will be saved into Picture_for_Presentation folder. (Not all the pictures will be saved into that folder, more graphs with different analysis will be inisde data_exploration.ipynb)



## Technologies Used
This project leverages several technologies to process and analyze election data efficiently:

- **Python**: The core language used for scripting the analysis, providing robust support for data manipulation and file handling.
- **Pandas**: A powerful library for data manipulation and analysis, used to handle, clean, and analyze the school and student data effectively.
- **Matplotlib**: A comprehensive library used for generating plots, charts, and visual representations of the data, enhancing the readability of the analysis.
- **hvPlot**: An interactive plotting library that extends the capabilities of Pandas and other libraries for easy creation of interactive maps and visualizations.
- **APIs (OpenWeatherMap & WHO and WorldBank)**: Used to gather real-time weather data (OpenWeatherMap) and mortality rate of different countries (WHO) and basic sanitation services in 5 countries (WorldBank).
- **Jupyter Notebook**: An interactive computing environment that facilitates data exploration, visualization, and narrative analysis, making it easy to document and present findings.
- **Visual Studio Code**: Chosen as the preferred Integrated Development Environment (IDE) for coding, debugging, and managing the project files.
- **GitHub**: Hosts the repository online, allowing for backup, sharing, and documentation hosting, including this README file.


## Credits

This project was independently developed by the following developers:
<br><br />

**Yiheng Sun**:

- **Github**: [@Sait0uAsuka](https://github.com/Sait0uAsuka)
  <br><br />

**Amina Mahfoud**:

- **Github**: [@Amina-MAHFOUD](https://www.linkedin.com/in/Amina-MAHFOUD)
  <br><br />

**Navdeep Grewal**:

- **Github**: [@Nav-hue](https://github.com/Nav-hue)
  <br><br />

**Golnaz Berenjian**:

- **Github**: [@Golnaz8](https://github.com/Golnaz8)
- **LinkedIn**: [@Golnaz Berenjian](www.linkedin.com/in/golnaz-berenjian)
  <br><br />


## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.