# Web-Application-Mimicking-Google-Sheets
This repository contains a web application that replicates key functionalities and the interface of Google Sheets. The project focuses on providing users with a spreadsheet-like interface, supporting mathematical operations, data quality features, and essential UI interactions.
Key Features:
Spreadsheet Interface:

Google Sheets-like UI: The application adopts a grid-based structure with toolbars, formula bars, and cell structures, closely mirroring Google Sheets.
Drag-and-Drop Functionality: Users can drag formulas, data, and selections across the grid.
Cell Dependencies: Formulas dynamically update based on cell references, ensuring accurate results.
Basic Formatting: Options to apply bold, italics, font size, and colors to cells.
Row and Column Management: Add, delete, and resize rows and columns as needed.
Mathematical Functions:

SUM: Adds a range of numbers.
AVERAGE: Calculates the average value of a selected range.
MAX/MIN: Determines the maximum or minimum value in a range.
COUNT: Counts numeric entries in a specified range.
Data Quality Functions:

TRIM: Removes leading and trailing spaces in cell text.
UPPER/LOWER: Converts text to uppercase or lowercase.
REMOVE_DUPLICATES: Eliminates duplicate rows within a selected range.
FIND_AND_REPLACE: Finds and replaces specific text within the spreadsheet.
Data Entry and Validation:

Supports data types like numbers, text, and dates.
Ensures numeric cells only accept valid numbers.
Testing:

A built-in testing framework allows users to validate their formulas and results interactively.
Bonus Features:
Advanced formulas with support for relative and absolute cell references.
Options to save and load spreadsheets for future use.
Data visualization capabilities like charts and graphs.
Additional data quality functions for enhanced usability.
Technologies Used:
Frontend: HTML5, CSS3, JavaScript (with libraries like React.js for UI rendering).
Backend (optional): Node.js/Flask for data persistence or advanced formula handling.
Database (optional): SQLite or MongoDB for saving spreadsheets.
Testing: Jest or Mocha for frontend and functional testing.
Challenges Solved:
Achieving high fidelity to the Google Sheets interface.
Implementing dynamic formula updates with efficient cell dependency tracking.
Supporting user-friendly data validation and error handling.
