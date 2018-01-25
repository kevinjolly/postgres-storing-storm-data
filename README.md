# postgres-storing-storm-data
Creating a database for the International Hurricane Watchgroup (IHW) in order to facilitate effective and consistent data sharing.

Obtained a CSV file from IHW which contains the following fields: 

- fid - ID for the row
- year - Recorded year
- month - Recorded month
- day - Recorded date
- ad_time - Recorded time in UTC
- btid - Hurricane ID
- name - Name of the hurricane
- lat - Latitude of the recorded location
- long - Longitude of the recorded location
- wind_kts - Wind speed in knots per second
- pressure - Atmospheric pressure of the hurricane
- cat - Hurricane category
- basin - The basin the hurricane is located
- shape_leng - Hurricane shape length

This project invovles creating a database for IHW that satisfies the following requirements: 

- Database for the IHW to store their tables.
- Table that contains the fields detailed in the CSV file
- User that can update, read, and insert into a table of the data.
- Insert the data into the table.
