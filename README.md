Bikeshare Data Analysis
=======================

This project provides an interactive Python script to explore US bikeshare data. Users can filter data by city, month, and day of the week, and receive descriptive statistics on various aspects of bikeshare usage.

Table of Contents
-----------------

-   [Overview](#overview)
-   [Date created](#date-created)
-   [Dataset Information](#dataset-information)
-   [Features](#features)
-   [Installation and Setup](#installation-and-setup)
-   [Usage](#usage)
-   [Requirements](#requirements)
-   [Sample Output](#sample-output)
-   [Credit](#credit)

Overview
--------

The `bikeshare.py` script allows users to analyze bikeshare data from three major US cities: Chicago, New York City, and Washington. It provides insights such as the most popular travel times, stations, trip durations, and user demographics.

Date Created
--------

This project and README file were created at 05/11/2024

Dataset Information
-------------------

This project uses CSV files containing bikeshare data for each city:

-   `chicago.csv`
-   `new_york_city.csv`
-   `washington.csv`

The data includes:

-   **Start Time**: Date and time the trip started.
-   **End Time**: Date and time the trip ended.
-   **Trip Duration**: Duration of the trip in seconds.
-   **Start Station** and **End Station**: Name of the start and end stations.
-   **User Type**: Type of user (Subscriber or Customer).
-   **Gender** and **Birth Year**: Available only for Chicago and New York City.

Features
--------

-   **Data Filtering**: Choose specific city, month, and day of the week to filter the data.
-   **Descriptive Statistics**:
    -   **Time Statistics**: Find the most common month, day, and hour for trips.
    -   **Station Statistics**: Find the most popular start and end stations and the most frequent combination of stations.
    -   **Trip Duration Statistics**: Display total, mean, median, min, max, and standard deviation of trip durations.
    -   **User Statistics**: Show counts of user types, gender distribution, and birth year data.
-   **Raw Data Display**: Optionally display 5 rows of raw data at a time.

Installation and Setup
----------------------

1.  Clone the repository to your local machine.

    bash

    Copy code

    `git clone https://github.com/rabbithunter0502/pdsnd_github.git`

2.  Navigate to the project directory.

    bash

    Copy code

    `cd pdsnd_github`

3.  Make sure you have Python 3 and pandas installed. You can install the required library with:

    bash

    Copy code

    `pip install pandas`

4.  Ensure the CSV files (`chicago.csv`, `new_york_city.csv`, `washington.csv`) are in the project directory.

Usage
-----

Run the script from the command line:

bash

Copy code

`python bikeshare.py`

1.  **City Selection**: Choose a city (Chicago, New York City, or Washington).
2.  **Filter Options**:
    -   **Month**: Choose a month (January to June) or "all" for no filter.
    -   **Day of Week**: Choose a day (e.g., Monday) or "all" for no filter.
3.  **Statistics Output**: The script will display the relevant statistics.
4.  **Raw Data Display**: You'll be prompted to view 5 rows of raw data iteratively.

Requirements
------------

-   Python 3.x
-   `pandas` library

To install pandas:

bash

Copy code

`pip install pandas`

Sample Output
-------------

After filtering, the script displays statistics like:

plaintext

Copy code

`Calculating The Most Frequent Times of Travel...

Most common month: June
Most common day of week: Wednesday
Most common start hour: 17

Calculating The Most Popular Stations and Trip...

Most commonly used start station: Columbus Circle
Most commonly used end station: Central Park
Most frequent trip combination: Columbus Circle to Central Park`

For additional raw data, the script will prompt:

plaintext

Copy code

`Would you like to see 5 lines of raw data? Enter yes or no:`

Credit
--------

-   **[Pandas Documentation](https://pandas.pydata.org/docs/)**

-   **[NumPy Documentation](https://numpy.org/doc/stable/)**

-   **[Python's Official Documentation](https://docs.python.org/3/)**

-   **[Stack Overflow](https://stackoverflow.com/)**
