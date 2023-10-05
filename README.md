# TOPSIS Analysis Python Script

## Overview
This Python script performs TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) analysis, a multi-criteria decision-making method.

## Usage
1. The script accepts input data, weights, and impacts as command-line arguments.

2. It validates the input data, ensuring it is in the correct format, and checks for non-numerical values.

3. The script also verifies that the number of weights and impacts matches the number of columns in the input data.

4. It normalizes the data and calculates TOPSIS scores based on the provided weights and impacts.

5. The output includes a dataframe with TOPSIS scores and rankings.

## Installation
```pip install topsis-sanchita-102003177```

## How to use it?
Open terminal and type topsis-sanchita-102003177 and then input
```topsis-sanchita-102003177 <input_data_file_name> <wt> <imp> <result_file_name>```

- `<input_data_file_name>`: Specify the name of the input data file (CSV format).
- `<weights>`: Provide the weights for each criterion, separated by commas.
- `<impacts>`: Indicate the impacts for each criterion, using '+' for positive and '-' for negative, separated by commas.
- `<result_file_name>`: Define the name of the output file where the results will be saved (CSV format).

## License
This repository is licensed under the MIT license. 
