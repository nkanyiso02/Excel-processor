# Excel Processor with Bar Chart

This Python script processes an Excel file containing transactions, applies a discount to prices, and generates a bar chart for the corrected prices.

## Features
- Reads an Excel file (`transactions.xlsx`)
- Applies a 10% discount to all values in the **3rd column**
- Saves corrected prices into the **4th column**
- Creates a bar chart for the corrected prices
- Outputs a new file: `updated_transactions.xlsx`

## Requirements
- Python 3.x
- [openpyxl](https://pypi.org/project/openpyxl/)

Install dependencies:
```bash
pip install openpyxl
