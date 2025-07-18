# Thailand Traffic Deaths ⚠️

This repository contains data and analysis related to traffic deaths in Thailand. The dataset includes various attributes such as the date of the incident, location, vehicle type, and more.

## 📄 Data Source
The data is sourced from the [Thai Traffic Deaths dataset](https://data.go.th/dataset/rtddi), avaiable on [Open Government Data](https://data.go.th/) platform.

## 📊 Exploratory Data Analysis (EDA)
The EDA is performed using a Jupyter Notebook, which includes data profiling and visualization to understand the dataset better. The analysis using `pandas` library and the profiling report generation using the `ydata_profiling` library.

## 🛠️ Requirements
The following software and libraries are required to run the analysis:

- Python 3.11 or later
- `Jupyter Notebook` or `JupyterLab` (for running the notebook)
- `pandas` (for data manipulation)
- `openpyxl` (for reading Excel files)
- `ydata_profiling` (for generating profiling reports)  
- `Poetry` (for dependency management)


## 📦 Installation
### Using Poetry
The dependencies managed using `poetry`. To set up the environment, ensure you have Poetry installed. If not, you can install it by following the instructions on the [Poetry website](https://python-poetry.org/docs/#installation).  

You can install the required packages by running:

```bash
poetry install
```
### Using pip
Alternatively, you can install the required packages listed in `requirement.txt` using pip . Run the following command:

```bash
pip install -r requirements.txt
```

## 📖 Usage

To run the EDA, you can open the `eda.ipynb` notebook in Jupyter Notebook or JupyterLab. The notebook contains the code to load the dataset, perform data profiling, and generate a report.


## 📄 Profiling Report
The profiling report is generated using the `ydata_profiling` library and saved as an HTML file. You can view the report to get insights into the dataset, including data types, missing values, and distribution of values.

## More analysis to come
Feel free to explore the dataset and contribute to the analysis. You can also fork the repository and submit pull requests for any improvements or additional analyses you would like to add. 