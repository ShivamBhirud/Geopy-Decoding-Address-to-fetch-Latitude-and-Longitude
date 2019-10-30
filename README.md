# Geopy-Decoding-Address-to-fetch-Latitude-and-Longitude
Decoding bulk amount of addresses from CSV file at once to get the latitudes and longitudes.

Geopy module is used in python for decoding the addresses. Usually, it takes a lot of time to decode addresses because of some restrictions on the APIs usage and limitations of our system. However, I tried to write a script that can keep going even after the occurrence of the service timeout error. For demo purposes, I have decoded 1000 addresses from the huge dataset, and it took me around half an hour to get the output. Yet, if someone wants to decode more than 1000 samples, then change the nrow=1000 (while loading the dataset) according to your needs.
Note that the input is taken from a CSV, and output is obtained and stored in another CSV file.

Installations required in python:
1. Pandas library
2. Numpy library
3. Geopy library
