# enielsen93-Hydraulic-Add-in
An Excel add-in designed by enielsen93, tailored for hydraulic specialists working in sewer system simulations. This tool brings commonly needed hydraulic and database functions into the Excel environment, enhancing workflows directly within spreadsheets.

Features
Colebrook-White Calculations
Calculate friction factors using the Colebrook-White equation (implicit solution) with support for both circular pipes and irregular cross-sections.

SQL Query Conversion
Convert values from a table column directly into a SQL WHERE clause, making it easy to query databases based on Excel data.

1D Linear Interpolation
Quickly perform linear interpolation in one dimension to streamline data analysis.

Installation
Download the Add-in File
Download the .xlam add-in file from this repository.

Enable the Add-in in Excel

Open Excel and go to File > Options.
Navigate to Add-ins.
At the bottom, select Excel Add-ins and click Go....
Click Browse and select the downloaded .xlam file.
Verify Installation
Once enabled, you should see the functions available in Excel.

Usage
Colebrook-White Calculation
Use the function =ColebrookWhite(diameter [m], material ("p" or "c"), slope [m/m]) to calculate full running flow for circular pipes or =ColebrookWhiteCRS(area[m²], wet perimeter [m], slope [m/m], Manning number) for irregular cross-sections.

SQL Query Conversion
Use macros in ribbon tab Regex to create SQL queries for use in QGIS, ArcMap, MIKE+ etc.

1D Linear Interpolation
Use =linterp(knownXs, knownYs, newX) for quick linear interpolation on a single variable.

Contributing
Contributions are welcome! Feel free to submit issues or pull requests to enhance functionality or improve documentation.
