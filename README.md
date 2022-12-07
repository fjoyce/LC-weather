# LC-weather: Las Cruces Biological Station weather data

## General Notes: 

I started exploring Las Cruces weather data in January 2021, initially to support a project aiming to use digital images to quantify forest structure (obviously light-dependent)

## Data sources  


- OTS weather data from an automated Campbell Scientific weather station, at 15-min intervals, are here: https://bixa.tropicalstudies.org/meteoro/default.php?pestacion=1

Name:	Las Cruces   
Coordinates:	8° 47' 7.27'' N, 82° 57' 32'' W   
Start date:	07/31/2008   
Manufacturer:	Campbell Scientific    

    - I downloaded the archived data for the historical data files:
        - Historical Data  
            - January, 1982 to December, 1985. File : LC_met_Jan05t_Jul08.csv (daily)
            - January, 2005 to August, 2008. (Davis Station)  

- Rather than redownloading data, I obtained files for 2008-08 through 2020-06 from Leland Werden on 2021-02-15.
    -  datos_meteorologicos_LC_Aug08_Jun20.csv (15-min intervals)          

- Since February 2021 I have periodically downloaded data from https://bixa.tropicalstudies.org/meteoro/default.php?pestacion=1, usually in monthly batches.
    - 2020: batches are in Las_Cruces_2020 subfolder; combined data are in LC_weather_2020.csv 
    - 2021: batches are in 2021 subfolder; combined data are in LC_weather_2021.csv
    - 2022: batches in 2022 subfolder; combined data are in LC_weather_2020.csv (within that subfolder)

## Missing data  


## Loma Linda 

-  Some daily weather data from Loma Linda are archived on the OTS website.
-  In this repo they are here: https://github.com/fjoyce/LC-weather/tree/main/data/Loma%20Linda   
-  Meteorological Station: Lomalinda
-  Location: 8° 44' 18.60'' N, 82° 55' 21.78'' W
-  Description: Manual rainfall and temperature data
-  Periods:  
    - From January 1973 to February 2008
    - From January 2010 to June 2011



