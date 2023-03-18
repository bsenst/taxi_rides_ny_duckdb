# Piperider Workshop

https://github.com/DataTalksClub/data-engineering-zoomcamp/blob/main/cohorts/2023/workshops/piperider.md

follow the instructions on https://github.com/InfuseAI/taxi_rides_ny_duckdb

open the duckdb OLAP-database `duckdb nyc_taxi.duckdb`

show the tables inside the duckdb database `SHOW TABLES;`

### Question 1:
What is the distribution between vendor id filtering by years 2019 and 2020 data?

**taxi_rides_ny_duckdb/.piperider/outputs/dev-20230318144751/index.html#/tables/fact_trips/columns/vendorid**

`70.1/29.6/0.5`

### Question 2:
What is the composition of total amount (positive/zero/negative) filtering by years 2019 and 2020 data?

**taxi_rides_ny_duckdb/.piperider/outputs/dev-20230318144751/index.html#/tables/fact_trips/columns/total_amount**

### Question 3:
What is the numeric statistics (average/standard deviation/min/max/sum) of trip distances filtering by years 2019 and 2020 data?

**taxi_rides_ny_duckdb/.piperider/outputs/dev-20230318144751/index.html#/tables/fact_trips/columns/trip_distance**
