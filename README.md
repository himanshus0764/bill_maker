# bill_maker
Bill Maker is a simple billing application available in both Python and C. It allows users to generate bills for services (e.g., flooring and tile work) by gathering details interactively and saving them as .xlsx (Python) or .csv (C) files.

# Bill Maker

**Bill Maker** is a simple billing application available in both Python and C. It allows users to generate professional bills for services such as flooring and tile work by gathering details interactively and saving the bill as a `.xlsx` file (Python) or `.csv` file (C). This project demonstrates how to handle file creation, user input, and formatting in both programming languages.

## Features

- **Interactive Input**: Users can input details like client name, address, bill number, service description, quantity, and rates.
- **File Output**:
  - **Python**: Bills are saved as formatted Excel files using the `xlsxwriter` library.
  - **C**: Bills are saved as CSV files for easy viewing and editing.
- **Multiple Entries**: Add multiple line items for services or products.
- **Safe Exit**: Both versions ensure that the file is saved before exiting.

## Usage

### Python Version
1. Install dependencies:
   ```bash
   pip install xlsxwriter pynput
