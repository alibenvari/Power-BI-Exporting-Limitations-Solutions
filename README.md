Power BI Exporting Limitation Solution
This repository contains a Python script that overcomes the exporting limitations of Power BI Desktop. The script exports data from a large dataset into multiple Excel files, bypassing the 30,000 record limit imposed by Power BI Desktop.

How it works
The script creates a separate Excel file for each unique agent in the dataset. Each Excel file contains the original dataset and a pivot table summarizing key metrics. If the dataset for a particular agent exceeds 30,000 records, it is split into five parts, each written to a separate sheet in the Excel file.

Usage
Clone the repository.
Update the dataset variable with your dataset.
Run the script.
Requirements
Python 3.6 or later
pandas
numpy
openpyxl
Please let me know if you have any questions or need further assistance! :))
