# ICASA-Dictionary
This is the official location for the ICASA Data Dictionary (IDD), which was previously hosted as a Google Sheet.
The IDD is accesible here in two formats:
1. XLSX - This is the full dictionary with all worksheets. The GitHub interface does not allow viewing the file contents, so if you want to use the workbook, you have to download to file. 
2. CSV - The CSV folder contains each worksheet. If you just need to search for individual terms, this may be an easier format to use since GitHub can display the content of each file.

As of 2025-07-11, we have introduced multiple changes. Most notably besides the CSV format, we have added a unique ID for each variable in the dictionary. For further information, please see the description of recent changes.
Included in the updates is implementation of a script using GitHub Actions that updates the XLSX version every time the CSV files are modified. This should ensure that the XLSX file is always synchronized with the CSV files.
