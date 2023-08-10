## Challenge

Main targets were to practice DAX time intelligence functions, looking at the housing market in the US state of Connecticut

## Requirements for this challenge 

- **Get data** from the Connecticut Housing Finance Authority using the following API endpoint: <https://data.ct.gov/resource/jpi8-zeza.json>
(hint: get data from web and pass in the API endpoint URL)
- **Get National data** to use as a comparison from: <https://dqydj.com/historical-home-prices/>
- **Create a date table** using DAX
  - Set your date table to begin in Jan of 2001 and end in Dec of 2020
- **Create relationships** between the Date column in your Date table and:
  - the Date column in your CT Housing Data table
  - the Date column in your National Housing Data table
- Using DAX to **create the following measures**:
  - Median sale price (hint: the source data already contains median by county and year, be careful!) for **Connecticut** and **National**
  - Year-over-year median sale price for **Connecticut** and **National**
  - Percent above/below national median home price
- **Create at least 2 visuals and a date slicer**
  - Column chart comparing YoY Median Housing Price Trend
  - Table containing Median Home Price and the Percent above/below national median home price
  - If you want to build an identical vizualization, add the sparklines comparing median home price and year-over-year gains.

## Solution

![image](https://github.com/EugeneZakharchenko/PowerBI_API/assets/110230661/8f8f3e5c-6e41-4067-be79-ee7f21a2c4f8)

![Recording 2023-08-10 161812](https://github.com/EugeneZakharchenko/PowerBI_API/assets/110230661/f84f00ab-87e7-4cfb-a851-f796cddb88bc)
