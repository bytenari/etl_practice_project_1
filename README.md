# etl_practice_project_1
complete ETL pipeline for accessing data from a website and processing it

### Project purpose
creating an automated script that can extract the list of all countries in order of their GDPs in billion USDs (rounded to 2 decimal places), as logged by the International Monetary Fund (IMF)


### Objects
Write a data extraction function to retrieve the relevant information from the required URL.

Transform the available GDP information into 'Billion USD' from 'Million USD'.

Load the transformed information to the required CSV file and as a database file.

Run the required query on the database.

Log the progress of the code with appropriate timestamps.

## Libraries 
python3.11 -m pip install requests 
python3.11 -m pip install pandas
python3.11 -m pip install numpy
python3.11 -m pip install bs4
python3.11 -m pip install datetime
