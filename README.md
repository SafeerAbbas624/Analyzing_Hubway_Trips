# Analyzing Hubway Trips

## Overview
This project involves analyzing Hubway bike-sharing data using SQL and Python. The dataset contains information about bike trips, including trip duration, start and end stations, user demographics, and more. The analysis aims to answer various analytical questions regarding user behavior and trip characteristics.

## Contents
- **SQL Analysis**: SQL queries to extract insights from the Hubway database.
- **Python Analysis**: Python scripts to further analyze the data and visualize results.
- **Data Cleaning**: Steps taken to clean and prepare the data for analysis.

## Dataset
The dataset consists of two main tables:
1. **Trips**: Contains information about each bike trip, including:
   - `id`: Unique identifier for each trip
   - `duration`: Duration of the trip in seconds
   - `start_date`: Start date and time of the trip
   - `start_station`: ID of the starting station
   - `end_date`: End date and time of the trip
   - `end_station`: ID of the ending station
   - `bike_number`: Unique identifier for the bike used
   - `sub_type`: User subscription type (Registered or Casual)
   - `zip_code`: User's zip code (for registered users)
   - `birth_date`: User's birth year (for registered users)
   - `gender`: User's gender (for registered users)

2. **Stations**: Contains information about the bike stations, including:
   - `id`: Unique identifier for each station
   - `station`: Name of the station
   - `municipality`: Municipality where the station is located
   - `lat`: Latitude of the station
   - `lng`: Longitude of the station

## Installation
To run the analysis, you need to have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python packages (install using pip):
  ```bash
  pip install jupysql pandas numpy sqlite3 zipcodes
  ```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/SafeerAbbas624/Analyzing_Hubway_Trips.git
   cd Analyzing-Hubway-Trips
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Execute the cells in the notebook to run the SQL queries and Python analysis.

## Analytical Questions
The project addresses several analytical questions, including:
- What was the duration of the longest trip?
- How many trips were taken by registered users?
- Which bike was used for the most trips?
- What is the average duration of trips by users over the age of 30?
- Which stations are most frequently used for round trips?

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Hubway for providing the dataset.
- The open-source community for the tools and libraries used in this project.

## Contact
For any questions or feedback, please reach out to [https://github.com/SafeerAbbas624].
