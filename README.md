# Openstreet-map-Analysis
An extensive analysis of the city I live in. Data auditing, wrangling and analysis using the OpenStreetMap data

The project documents the data collection, data wrangling, data auditing and generation of insights in Python and SQL. The project makes use of OpenStreetMap OSM XML data for Mumbai region (My Home City). The project repository consists of following:

1. **sample.osm**: A sample of the larger dataset used in the project. The original file on which data wrangling was performed was over 420 MB in size.

2. **Map Area.txt**: This text document provides the link to the website to access the complete dataset and also a brief description of the area and the reason for chosing this particular area.

3. **Data Cleaning and Wrangling Code.ipynb**: This jupyter notebook commit documents the entire code used for data wrangling. It imports the OSM XML file, performs the requisite auditing, exports the cleaned data in CSV format in the mentioned schema and also documents the code for its import as tables into the SQL database.

4. **Final Report Detailing Findings.ipynb**: This jupyter notebook is a report which summarizes some of the problems encountered in the dataset and the requisite auditing performed. It also makes used for the db-API library (sqlite3) library, which enabled me to write and execute SQL queries in python to perform some basic analytics. This analytics helps us to gain important insights (about Mumbai city) from the dataset.

*OpenStreetMap (OSM) is a collaborative project to create a free editable map of the world. The creation and growth of OSM has been motivated by restrictions on use or availability of map information across much of the world, and the advent of inexpensive portable satellite navigation devices.*
