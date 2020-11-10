## Udacity Data Steaming NanoDegree Project 1: Optimizing Public Transit

#### Project rubric can be found here: https://review.udacity.com/#!/rubrics/2660/view

## Purpose

#### In this project, I created a streaming event pipeline using the Apache Kakfa ecosystem to assist the Chicago Travel Authority simulate and display the status of trains in real time via a website.

#### This project is intended to display my knowledge of Apache Kafka, Avro, Faust Steam, and KSQL

## ETL Process

#### Turnstile and weather data are loaded into Kafka via Kafka Connect and REST Proxy, before being consumed by a Travel Status consumer. Faust stream processing is used to convert raw train station data ingested by Kafka Connect. KSQL is also used to aggregate turnstile data for each station

##### The directories contain files creating Kafka Producers and Consumers and defining Avro schemas.
