# Enhanced Cost and Resource Spreadsheet

## Description

This HTML file (`PainelEstrutura.html`) implements a dynamic spreadsheet for managing costs and resources. The spreadsheet is structured into categories (e.g., Infrastructure, Equipment) and allows adding, removing, and editing items within each category. Calculations for the total value per item and totals per category are performed automatically. The spreadsheet also offers functionalities to export the data to PDF and Excel, along with a function to clear all entered data.

## Features

* **Category Management:** The spreadsheet is organized into multiple categories for better organization of cost and resource items.
* **Add/Remove Items:** Users can add new rows (items) to each category and remove existing items.
* **Dynamic Editing:** Input fields (item, quantity, unit value, depreciation) are editable, and calculations are updated in real-time.
* **Automatic Calculation:** The total value of each item is calculated automatically (quantity \* unit value).
* **Category Totals:** The spreadsheet calculates and displays totals for each category (total value and depreciation).
* **Grand Totals:** The spreadsheet calculates and displays the overall totals for the entire spreadsheet.
* **PDF Export:** The spreadsheet data can be exported to a PDF file.
* **Excel Export:** The spreadsheet data can be exported to an Excel file.
* **Data Filtering:** A search field allows filtering items across all tables.
* **Clear Data:** A function allows clearing (removing) all data entered in the spreadsheet.
* **Column Sorting:** Table columns can be sorted by clicking on the column headers.

## Technologies Used

* **HTML:** Page structure.
* **CSS (Tailwind CSS):** Page styling for a user-friendly and responsive interface.
* **JavaScript:** Spreadsheet logic (calculations, adding/removing rows, exporting, filtering, sorting).
* **html2pdf.js:** JavaScript library to export the spreadsheet to PDF.
* **xlsx (js-xlsx):** JavaScript library to export the spreadsheet to Excel.
* **Google Fonts (Inter):** Font used on the page.

## File Structure

The HTML file contains the following main sections:

* **Header:** Spreadsheet title.
* **Global Actions:** Toolbar with buttons for searching, exporting (PDF/Excel), and clearing data.
* **Main Area:** Contains the data tables, organized by category. Each category has:
    * Category title.
    * Table with headers (Item, Quantity, Unit Value, Total Value, Depreciation, Actions).
    * Table body (data rows).
    * Table footer (category totals).
    * "Add Item" button.
* **General Summary:** Displays the overall totals of the spreadsheet.
* **Usage Instructions:** Provides guidelines on how to use the spreadsheet.
* **JavaScript:** Contains the JavaScript code for the spreadsheet functionality.

## How to Use

1.  Open the `PainelEstrutura.html` file in a web browser.
2.  Use the "Add Item" buttons to include new rows in the tables.
3.  Fill in the input fields in the table rows.
4.  Total values are calculated automatically.
5.  Use the export buttons to generate PDF or Excel files.
6.  Use the search field to filter items.
7.  Use the "Clear Data" button to erase all data (use with caution).
8.  Click on the column headers to sort the data.

## Notes

* The file uses Tailwind CSS for styling, which facilitates creating a modern and responsive interface.
* The `html2pdf.js` and `xlsx` libraries are used for the export functionalities.
* The JavaScript code is responsible for all the interactivity of the spreadsheet, including calculations, DOM manipulation, and data export.
