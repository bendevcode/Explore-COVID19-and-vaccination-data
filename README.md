# Explore-COVID19-and-vaccination-data
An application that allows users to explore some of the most interesting aspects of the Covid-19 datasets

-Project Title: "Explore-COVID19-and-vaccination-data"

**OVERVIEW**

This project aims to develop an application that allows users to explore and analyze two datasets related to the Covid-19 pandemic. The objective is to use the data to uncover interesting insights and patterns that can help users better understand the impact of the pandemic.

The primary tool for analyzing the data will be the Python library Pandas, which is well-suited for working with large datasets. The project will also incorporate visualizations as a means of illustrating the results of the analysis.

The dataset that will be used for this project contains some missing values, and the project will need to take this into account when analyzing the data. Possible techniques for handling missing data may include imputation or exclusion of missing values.

The end goal of the project is to develop an application that is user-friendly and easy to navigate, with clear and informative visualizations that allow users to quickly understand the key findings from the data analysis.


**DATA**

The dataset used in this project was obtained from a publicly available source. Two datasets were explored for these projects namely; worldometer.csv and country_vaccinations.csv worldometer.csv, is a comma separate file containing the following columns:

• Country/Region - this is the country for which the data is provided;

• Continent – Continent information with regards to a country;

• Population – The population of a specific country at that time;

• Total Cases - The absolute number of cases in a particular country;

• Total Deaths - The absolute number of deaths in a particular country;

• Total Recovered - The absolute number of recovered patients in a particular country;

• Active cases – Number of active patients in a particular country at the time the data
was collected;

• Serious/Critical - Number of serious/critical patients in a particular country at the time
the data was collected;

• Tot Cases/1M pop – Total number of cases divided by 1 million (normalised);

• Deaths/1M pop - Total number of deaths divided by 1 million (normalised);

• Total Tests - The absolute number of tests performed by a particular country;

• Tests/1M pop - Total number of tests divided by 1 million (normalised);

The second, country_vaccinations.csv, is a comma separate file containing the following
columns:

• Country - this is the country for which the vaccination information is provided;

• Country ISO Code - ISO code for the country;

• Date - date for the data entry; for some of the dates we have only the daily vaccinations, for others, only the (cumulative) total;

• Total number of vaccinations - this is the absolute number of total immunizations in the country;

• Total number of people vaccinated - a person, depending on the immunization
scheme, will receive one or more (typically 2) vaccines; at a certain moment, the number of vaccination might be larger than the number of people;

• Total number of people fully vaccinated - this is the number of people that receivedthe entire set of immunization according to the immunization scheme (typically 2); at a certain moment in time, there might be a certain number of people that received one vaccine and another number (smaller) of people that received all vaccines in the scheme;

• Daily vaccinations (raw) - for a certain data entry, the number of vaccination for that
date/country;

• Daily vaccinations - for a certain data entry, the number of vaccination for that
date/country;

• Total vaccinations per hundred - ratio (in percent) between vaccination number and
total population up to the date in the country;

• Total number of people vaccinated per hundred - ratio (in percent) between
population immunized and total population up to the date in the country;

• Total number of people fully vaccinated per hundred - ratio (in percent) between
population fully immunized and total population up to the date in the country;

• Number of vaccinations per day - number of daily vaccination for that day and
country;

• Daily vaccinations per million - ratio (in ppm) between vaccination number and total
population for the current date in the country;

• Vaccines used in the country - total number of vaccines used in the country (up to
date);

• Source name - source of the information (national authority, international
organization, local organization etc.);

• Source website - website of the source of information;

**Methodology**

The analysis was carried out in Python. The following steps were taken:

- Created a function that will generate a stacked barplot with the following data, Total
cases, Total recovered and Total Death (in this order) for countries in a specific
continent. The continent name has to be provided by the user. Also, print the country
with most and least number of Total cases

- Created a function to define the relationship between the Total Recovered and Total
Deaths of patients in a specific continent, Using the seaborn lmplot.

- Created a function that first prints the number of entries in the dataset for each
continent. It then generates a barplot per continent containing the number of
tests/1M per continent. Normalise the data before creating the barplot by dividing the
total sum of tests per country in a continent by the number of countries in the
continent.

- Used the second dataset to create a line plot of Daily Vaccinations on the y-axis and
date on the x-axis of a particular country.

- Created a main() function containing a menu to run the functions


**USAGE**

The code for this project is provided in the Jupyter notebook file explorecovid.ipynb. The following libraries are required to run the code:

-pandas

-numpy

-seaborn

-matplotlib

To run the code, make sure you have these libraries installed and then open the notebook file in Jupyter and run the cells.

**CONCLUSION**

The project provides insights into the impact of covid 19 and the vaccinations taking place.

**COLLABORATION**

Please feel free to use this code and dataset for your own projects. If you have any questions or suggestions, please do not hesitate to contact me or open an issue on this GitHub repository.

**CONTACT**

You can reach me at:

Email: bencharlogh@gmail.com
LinkedIn: [My LinkedIn Profile](https://www.linkedin.com/in/oluyori/)
