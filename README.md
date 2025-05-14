# bcehs-wait-times
Ambulance response times for B.C. Emergency Health Services, by event type, 2018-2024. See included fact sheet for detailed definitions of call types.

## AIS Data Dictionary (ships-data.csv)
| Variable | Format | Description 
| --- | --- | --- |
| AisVersion | int | Either 1 or 2 | Class A === 2, Class B === 2 
| community | text | Community name
| year | int | year
| events-total | int | Total number of calls
| events-red_purple | int | Number of red/purple calls (immediately life threatening or time critical)
| events-orange | int | Number of orange calls (urgent potentially serious)
| events-yellow | int | Number of yellow calls (non-urgent)
| median-seconds-red_purple | int | Median response time for red/purple calls (in seconds)
| median-seconds-orange | int | Median response time for orange calls (in seconds)
| median-seconds-yellow | int| Median response time for yellow calls (in seconds)