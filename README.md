# DataIncubator_SFMTA_Analysis
Data project for The Data Incubator program

For San Francisco residents and tourists who visit the city, transportation is always a big headache. Public transportations are confusing and hard to navigate from one place to another. For people who choose to drive, finding a parking place takes forever. My project at Data Incubator hopes to tackle the parking issue by analyzing parking meter transaction data at downtown San Francisco.

I hope to understand more deeply about what factors cause the parking issue, and if we can predict what's the optimal number of parking spots at each downtown area. I want to make it easier for people to find parking spaces in the city, but also to avoid having too many lots emptyat the same time. I would like to know what are some areas I can help improve the current parking situation. I hope to propose a improvement plan for the city transportation department and to make the parking hunting process more tolerable.

Data Size: up to 6GB, to perform the experiment, just use first 300,000 records
Data source- I used a provided API from  https://data.sfgov.org/Transportation/SFMTA-Parking-Meter-Detailed-Revenue-Transactions/imvp-dq3v

What I did in the following code:
1. Fetch data through API
2. Clean data, find more meaningful data fields
3. Draw two plots
Plot - 1: Parking counts, rev and total ocupation hours by parking lot
Plot - 2: Parking counts, rev and total ocupation hours by weekday
