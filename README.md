# python_geopyFlask

This application gives a html front end to user and option to upload a csv file of addresses. Python reads that csv file extracts address from the csv
file. Those addresses are passed to geo py which gives their latitude and longitude. These are again written back to the same csv file and 
provided for the user to download. 

Python libraries used
1) flask http://flask.pocoo.org/
2) geopy.geocoders https://github.com/geopy/geopy
3) datetime
