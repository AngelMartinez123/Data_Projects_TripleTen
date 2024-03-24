# TripleTen 'Zuber Ride-Sharing Company Data Analysis Project'

## Description

This project involves conducting exploratory data analysis (EDA) on a database containing information on taxi rides in Chicago, with the goal of understanding passenger preferences and the impact of external factors on rides for Zuber, a new ride-sharing company launching in the city. The database consists of several tables including neighborhoods, cabs, trips, and weather_records, each containing relevant data points such as ride duration, distance, pickup/dropoff locations, weather conditions, and more.

The data was spread across four tables:

- `'neighborhoods'`: data on city neighborhoods
    - `'name'`: name of the neighborhood
    - `'neighborhood_id'`: neighborhood code
- `cabs`: data on taxis
    - `'cab_id'`: vehicle code
    - `'vehicle_id'`: the vehicle's technical ID
    - `'company_name'`: the company that owns the vehicle
- `trips`: data on rides
    - `'trip_id'`: ride code
    - `'cab_id'`: code of the vehicle operating the ride
    - `'start_ts'`: date and time of the beginning of the ride (time rounded to the hour)
    - `'end_ts'`: date and time of the end of the ride (time rounded to the hour)
    - `'duration_seconds'`: ride duration in seconds
    - `'distance_miles'` : ride distance in miles
    - `'pickup_location_id'` : pickup neighborhood code
    - `'dropoff_location_id'` : dropoff neighborhood code
- `weather_records`
    - `'record_id'`: weather record code
    - `'ts'`: record date and time (time rounded to the hour)
    - `'temperature'` : temperature when the record was taken
    - `'description'` : brief description of weather conditions, e.g. "light rain" or "scattered clouds"

## Tasks

### Exploratory Data Analysis (Tasks 1-4)

1. **Data Cleaning and Preparation**: Cleaning and preparing the dataset for analysis, ensuring data integrity and consistency.
2. **Neighborhood Analysis**: Analyzing data from the neighborhoods table to understand neighborhood characteristics and distribution.
3. **Taxi Analysis**: Examining data from the cabs table to gain insights into taxi companies and vehicle information.
4. **Ride Analysis**: Analyzing data from the trips table to identify patterns in ride duration, distance, and pickup/dropoff locations.


### Investigative Analysis (Tasks 5-7)

1. **Impact of Weather on Ride Duration**: Investigating whether weather conditions have an impact on ride duration by linking data from the trips and weather_records tables.
2. **Analysis of Rides from the Loop to O'Hare International Airport**: Examining the duration of rides from the Loop to O'Hare International Airport on rainy Saturdays to determine if there are any significant changes.

## Data Sources

- **Neighborhoods Table**: Contains data on city neighborhoods including names and neighborhood IDs.
- **Cabs Table**: Provides information on taxis including vehicle codes, technical IDs, and company names.
- **Trips Table**: Contains data on rides including ride codes, vehicle codes, ride start/end times, duration, distance, and pickup/dropoff neighborhood IDs.
- **Weather_Records Table**: Provides weather data including record IDs, date/time, temperature, and weather description.

## Methodology

The analysis will involve data manipulation, visualization, and statistical techniques to uncover insights and patterns in the dataset. Techniques such as JOIN operations will be used to link data from different tables, and exploratory data visualization will be employed to visualize trends and relationships.

## Deliverables

The deliverables for this project will include a comprehensive report outlining the findings from the exploratory data analysis and investigative analysis, along with visualizations to support key insights. Additionally, a readme file will be provided summarizing the project objectives, tasks, data sources, methodology, and key findings.

## Conclusion

Through this analysis, Zuber aims to gain valuable insights into passenger preferences and factors influencing ride behavior in Chicago, enabling the company to make informed decisions and optimize its services for success in the competitive ride-sharing market.
