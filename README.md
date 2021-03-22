# PyBer Analysis
## Overview
We were asked to get a sample of weekly fares and show its relation between the three city types. The city types are:
-	Urban 
-	Suburban
-	Rural

This summary will be in a DataFrame format, additionally, a line graph will help to demonstrate the difference in variations between the city types.

## Results 
Figure1 Shows the unformatted DataFrame using “city type” as the index and values are as follows:
- ride_id (record for each ride that are serviced, from PyBer)
- driver_count  (the amount that are registered in PyBer) and 
- fares (fares rendered by the service).
![image](https://user-images.githubusercontent.com/78861458/111925974-46501600-8a81-11eb-88eb-2429aaf9b524.png)

Figure2. The formatted DataFrame for Figure1
![image](https://user-images.githubusercontent.com/78861458/111926080-c1b1c780-8a81-11eb-99bb-5cc259393358.png)

Figure3. The  reset index "date" and "type" DataFrame using "fares" as values (columns).
![Figure3](https://user-images.githubusercontent.com/78861458/111926495-5ec13000-8a83-11eb-9813-3c9edea84d98.png)

Figure4. loc() function was used to highlight the time frame that was required to do the analysis
for PyBer service on the three city type.
![Figure4](https://user-images.githubusercontent.com/78861458/111926811-b14f1c00-8a84-11eb-96a5-048473bb9584.png)

Figure8 Shows the DataFrame line plot for the three city type. 
![Figure8](https://user-images.githubusercontent.com/78861458/111927047-9e891700-8a85-11eb-97b8-3cbfb30b632c.png)

## Summary
The highest revenue earner for PyBer is the Urban cities, however Urban cities average fares are three times less than that in Rural areas. This is within reason that demographically more people live in urban areas than rural with suburban in the middle. From the graph “Total Fares by City Type” all three cities type show similar trends with the highest point for all between the month of February and March. The slight difference with Suburban have increasing demands towards the end of April.  More drivers could be placed in Rural and Suburban cities so as to attract more customers to generate more service since the fluctuation in fares for the period seems flat.

