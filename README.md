# Project Description
- for: Assignment-1(UCS654)
- Submitted by: Himanshu Bansal
- Roll no: 102103568
- Group: 3COE20

# TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)

This Python script implements the TOPSIS method for multi-criteria decision-making. It takes a CSV file containing a decision matrix, weights, and impacts as input, and produces a ranked result based on the TOPSIS score.

## Usage

- `InputDataFile`: Path to the CSV file containing the decision matrix.
- `Weights`: Comma-separated weights for each criterion.
- `Impacts`: Comma-separated impact direction for each criterion (`+` for maximization, `-` for minimization).
- `ResultFileName`: Name of the file to save the TOPSIS results.

## Requirements

- Python 3
- pandas
- numpy

## Input File Format

## Output

The script generates a CSV file containing the TOPSIS score and rank for each object:


## Error Handling

- If the input file is not found, an error message will be displayed.
- If the number of weights, impacts, or columns in the decision matrix is incorrect, a `ValueError` will be raised.
- If the columns from the 2nd to the last do not contain numeric values, a `ValueError` will be raised.
- Any unexpected errors during the execution will be displayed.

```
