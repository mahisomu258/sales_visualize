# Diwali Sales Data Analysis Project

## Project Overview

This project is aimed at beginners in Python and data analysis. The goal is to analyze Diwali sales data to uncover insights that can help improve customer experience and increase sales. By the end of this project, you will have hands-on experience with data cleaning, exploration, visualization, and basic statistical analysis using Python.

## Table of Contents

1. [Project Structure](#project-structure)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Dataset](#dataset)
5. [Usage](#usage)
6. [Analysis Steps](#analysis-steps)
7. [Conclusion](#conclusion)
8. [Contributing](#contributing)
9. [License](#license)

## Project Structure

```
Diwali_Sales_Analysis/
├── data/
│   └── diwali_sales_data.csv
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_data_exploration.ipynb
│   ├── 03_data_visualization.ipynb
│   └── 04_statistical_analysis.ipynb
├── src/
│   ├── data_cleaning.py
│   ├── data_exploration.py
│   ├── data_visualization.py
│   └── statistical_analysis.py
├── README.md
└── requirements.txt
```

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/Diwali_Sales_Analysis.git
   cd Diwali_Sales_Analysis
   ```

2. Create a virtual environment and activate it:

   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:

   ```sh
   pip install -r requirements.txt
   ```

## Dataset

The dataset used in this project contains sales data during the Diwali season. It includes various fields such as:

- Customer ID
- Product Category
- Gender
- Age
- Purchase Amount
- Marital Status
- City Category
- Stay in Current City
- ...and more

Ensure the dataset file (`diwali_sales_data.csv`) is placed in the `data/` directory.

## Usage

1. Open Jupyter Notebook:

   ```sh
   jupyter notebook
   ```

2. Navigate to the `notebooks/` directory and start with `01_data_cleaning.ipynb`.

3. Follow the sequence of notebooks to perform data cleaning, exploration, visualization, and analysis.

## Analysis Steps

### 1. Data Cleaning

- Handle missing values
- Remove duplicates
- Format and normalize data

### 2. Data Exploration

- Understand the structure and contents of the data
- Generate summary statistics
- Identify patterns and trends

### 3. Data Visualization

- Create visual representations of data (bar plots, histograms, scatter plots, etc.)
- Use visualization to communicate findings effectively

### 4. Statistical Analysis

- Perform basic statistical tests
- Analyze relationships between variables
- Draw actionable insights

## Conclusion

Summarize your findings from the analysis and provide recommendations for improving customer experience and increasing sales during the Diwali season.

## Contributing

Contributions are welcome! Please create a fork of the repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Happy analyzing and have a wonderful learning experience!
