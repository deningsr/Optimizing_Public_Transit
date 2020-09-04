# Optimizing Public Transit

# In this project, I created a streaming event pipeline using the Apache Kakfa ecosystem to assist the Chicago Travel Authority simulate and display the status of trains in real time via a website.

# Turnstile and weather data are loaded into Kafka via Kafka Connect and REST Proxy, before being consumed by a Travel Status consumer.
# Faust stream processing is used to convert raw train station data ingested by Kafka Connect. KSQL is also used to aggregate turnstile data for each station

# The directories contain files creating Kafka Producers and Consumers and defining Avro schemas.
