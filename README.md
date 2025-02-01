# Energy Community Forecasting

**Final Project Group:** Ivan Duvnjak, Enkh-Oyu Nomin, Oleg Lastocichin

## Overview

This project focuses on forecasting energy consumption within a community using advanced time series analysis and machine learning techniques. Accurate energy demand forecasting is crucial for efficient energy management, grid stability, and integrating renewable energy sources.

## Table of Contents

- [Project Structure](#project-structure)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Structure

The repository is organized as follows:

- `ts_final_project.ipynb`: Main Jupyter Notebook containing the project's code and analysis.
- `environment.yml`: Conda environment file listing the dependencies required to run the project.
- `lightning_logs/`: Directory containing training logs from PyTorch Lightning.
- `neural_forecaster_model_*`: Directories storing trained neural network models.
- `lic_meteo`, `lic_meters`, `lic_nwp`: Directories containing license information for meteorological, meter, and numerical weather prediction data, respectively.
- `.gitattributes` and `.gitignore`: Configuration files for Git.
- `README.md`: Project documentation (this file).

## Data Sources

The project utilizes the following datasets:

- **Energy Consumption Data:** Hourly energy usage data collected from community meters.
- **Meteorological Data:** Weather information such as temperature, humidity, and wind speed.
- **Numerical Weather Prediction (NWP) Data:** Forecasted weather parameters to enhance prediction accuracy.

*Note: Ensure compliance with the licensing terms provided in the `lic_meteo`, `lic_meters`, and `lic_nwp` directories when using these datasets.*

## Methodology

Our approach includes:

1. **Data Preprocessing:** Cleaning and integrating energy consumption data with meteorological and NWP data.
2. **Feature Engineering:** Creating relevant features to capture temporal patterns and external influences on energy consumption.
3. **Model Development:** Implementing and training neural network models for time series forecasting.
4. **Model Evaluation:** Assessing model performance using appropriate metrics and validation techniques.

## Installation

To set up the project environment:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Hanuro/Energy-community-forecasting.git
   cd Energy-community-forecasting
   ```

2. **Create and Activate Conda Environment:**

   ```bash
   conda env create -f environment.yml
   conda activate energy-forecasting
   ```

*Note: The `environment.yml` file contains all necessary dependencies.*

## Usage

To run the analysis:

1. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

2. **Open and Execute:**

   Open `ts_final_project.ipynb` and execute the cells sequentially to reproduce the analysis and results.

*Ensure that all required data files are available and paths are correctly set within the notebook.*

## Results

The project demonstrates the effectiveness of neural network models in forecasting community energy consumption. Detailed results, including performance metrics and visualizations, are available in the `ts_final_project.ipynb` notebook.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to thank our instructors and peers for their support and guidance throughout this project.
