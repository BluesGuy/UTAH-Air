Weather Balloon station data

    Station identifier: SLC
    Station number: 72572
    Station latitude: 40.77
    Station longitude: -111.95
    Station elevation: 1289.0
    
Sample content from Balloon2013to072514.csv.gz file (first 6 lines):

date,time,PRES (hPa),HGHT (m),TEMP (C),DWPT (C),RELH (%),MIXR (g/kg),DRCT (deg),SKNT (knot),THTA (K),THTE (K),THTV (K)
01 Jan 2009,00:00,1000.0,187,,,,,,,,,
01 Jan 2009,00:00,925.0,818,,,,,,,,,
01 Jan 2009,00:00,872.0,1289,1.4,-3.6,69,3.38,350,4,285.5,295.4,286.1
01 Jan 2009,00:00,868.0,1326,1.6,-4.4,64,3.19,344,4,286.1,295.5,286.6
01 Jan 2009,00:00,850.0,1497,2.0,-6.0,55,2.89,318,7,288.2,296.8,288.7

DATA SOURCE:

Weather Balloon Data from SLC Airport

Data gathered and cleaned by Brad Stone (brad@stonefoundation.net).
2014-08-19
Version: 0.12.1

This data was gathered from: 
http://weather.uwyo.edu/upperair/sounding.html

The data was gathered for each month from January 1973 through July 2014 for
readings at the Salt Lake City Airport (Station #72572). 

Readings are taken twice a day at 0:00 UTC and 12:00 UTC and data is available
for multiple elevations each reading.

Each file was then processed in order to convert the HTML output a CSV file.

NOTE: Some data is not available for every date - especially in the early years.


WeatherBalloonSLC-v0.12.csv = all of the weather balloon for each day at each elevation.
StationOut-v0.12.1.csv = readings on the ground for each day.

***NOTE:  StationOut still needs additional processing.The data file contains alternating
lines of comma separated keys and then comma separated values. The problem is that the
keys aren't always the same for every date.

We need someone to read in this data, and create a CSV file that contains a header with all
of the keys. Nulls should appear in the columns for dates that don't have information from certain keys.

+++ END DATA sOURCE ++++




