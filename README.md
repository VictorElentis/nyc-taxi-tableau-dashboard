# NYC Taxi Dashboard (Tableau Public)

An interactive Tableau dashboard of NYC yellow taxi trips for March 2019.

**[View the live dashboard on Tableau Public](https://public.tableau.com/app/profile/victor.chigbu/viz/Book1_17939180919160/NYCTaxiDashboardMarch2019)**

## What it shows

- **Revenue by Borough:** total fare revenue for Manhattan, Queens, Brooklyn and the Bronx
- **Daily Revenue:** revenue for each day of the month
- **Top 10 Pickup Zones by Revenue:** the busiest pickup areas, led by JFK and LaGuardia airports
- **Trips by Hour:** the number of trips in each hour of the day

Clicking a borough in the first chart filters the other three charts to that borough.

## Data

`taxi_trips_for_tableau.csv` contains 6,400+ trips from the seaborn `taxis` sample dataset, with added columns for borough, weekday and tip percentage.

## Tools

Tableau Public (calculated fields, filters, dashboard actions). The data was prepared with Python and SQL; see my [NYC Taxi SQL analysis](https://github.com/VictorElentis) project.
