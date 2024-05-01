# Property Data Generator

## Overview
`propertyDataGenerator.py` is a Python script designed to collect data about properties through user input in the terminal and store the data in an Excel workbook. It allows users to enter information about different properties, which is then organized into sheets within an Excel workbook named `properties_for_sale.xlsx`. Each property's data is stored on a new sheet named after the property's address.

## Features
- **Data Collection**: Interactively gathers data via command-line prompts.
- **Excel Integration**: Utilizes the `openpyxl` library to create and manage Excel workbooks.
- **Dynamic Sheets**: Creates a new sheet for each property based on its address.
- **Zone Links**: Includes handling for zoning information with links to detailed descriptions.

## Prerequisites
Before you run the script, ensure you have Python installed on your system. The script is compatible with Python 3.6 and later. You also need to install the required Python packages:

```bash
pip install openpyxl
```

## Installation
1. Clone this repository or download the propertyDataGenerator.py and zones.py files to your local machine.

2. Navigate to the directory containing the downloaded files.

## Usage

To run the script, simply execute the following command in the terminal:

python3 propertyDataGenerator.py

## Configuration

Excel Workbook: The default workbook name is properties_for_sale.xlsx. It can be modified in the script if needed.

Zone Definitions: Edit the zones.py file to update or add new zone definitions as required.

## Contributing

Feel free to fork this repository and submit pull requests to enhance the functionalities of the propertyDataGenerator.py script.