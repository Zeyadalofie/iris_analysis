# Iris Dataset Analysis

## Project Overview

This project focuses on building a Python data analysis project using uv,loading a dataset with Pandas, performing basic data exploration and analysis, and exporting the results to CSV files.


## Project Structure

```text
iris-analysis/
├── data/
│   └── iris.csv
├── output/
│   ├── species_summary.csv
│   └── filtered_iris.csv
├── iris_analysis.ipynb
├── pyproject.toml
├── uv.lock
└── README.md
```


## Features

- Dataset inspection and exploration
- Missing value and duplicate row detection
- Species distribution analysis
- Descriptive statistics and mean calculations
- Data filtering and sorting
- Exporting analysis results to CSV files

## Dataset

The project uses the Iris dataset from the Seaborn GitHub repository.

**Source:** [Iris Dataset (CSV)](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv)

The dataset contains measurements of Iris flowers, including sepal length, sepal width, petal length, petal width, and species.

## Requirements

- Python
- [uv](https://docs.astral.sh/uv/)
- Pandas
- Jupyter Notebook

## Installation

To clone this repository: 

```bash
git clone https://github.com/Zeyadalofie/iris_analysis.git
```


Install the project dependencies:

```bash
uv sync
```

Download the dataset into the `data` directory if it is not already available:

```bash
mkdir -p data
curl -L https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv -o data/iris.csv
```

## Usage

Start Jupyter Notebook:

```bash
uv run jupyter notebook
```

Open `iris_analysis.ipynb` and run the notebook cells to explore the dataset and perform the analysis.

## Output

The analysis generates the following CSV files in the `output` directory:

- `species_summary.csv` — descriptive statistics grouped by Iris species.
- `filtered_iris.csv` — flowers with a sepal length greater than 6.

## Technologies

- Python
- Pandas
- Jupyter Notebook
- uv
- CSV

## License

This project was created for educational purposes as part of a Python data analysis assignment.

