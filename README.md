
# surfs_up

Software used:
 -  Python
 -  SQL Lite
 -  sqlAlchemy
 -  matplotlibs
 
## Overview of the analysis: 

_The purpose of the analysis is to evaluate if the planned investment for an ice cream shop in Oahu is sustainable year-round. In order to determine this
we specifically look at temperature data for the months of June and December._

## Results: 


### Major points derived from the analysis
  
  - The average temperature is 71°F in December and 74°F in June.
  - The minimum temperature in December with 56°F is 8 degrees lower than the temperature in June with 64°F. The maximum temperature is 2 degrees lower with 83°F in December   versus 85°F in June. 
  - Only 25% of the temperatures are at or under 69°F for December and 73°F in June. 
  - 75% of the temperatures are at or above 74°F for December and at or above 77°F in June.
---
  June   
  
  ![image](https://user-images.githubusercontent.com/91682586/145416385-cb7f2648-c203-47a1-aec9-3487d39531bb.png)
  
  December   
  
  ![image](https://user-images.githubusercontent.com/91682586/145416215-67098b3e-823c-4801-842b-96e8de5fdaed.png)

---
 - These 2 histograms show the frequencies and distribution of the temperatures for each month.
 
  June      
  
  ![image](https://user-images.githubusercontent.com/91682586/145417812-5e059728-611f-4c7a-862e-fd8b05926a1f.png)
    
  December   
  
  ![image](https://user-images.githubusercontent.com/91682586/145417866-93045ff6-cbf9-4ea0-8a22-920785136b9f.png)

  The histograms show a relatively even distribution with the highest frequency of temperatures in the low 70s.
  
 Summary:
 
 The temperatures in Oahu are very similar in both months with average temperatures in the low 70s. They are suitable for a surf & ice cream shop.
 The low variance in temperatures will make it easy to plan. 
 
 Our potential investor was also concerned if it will rain too much. Therefore I am including an additional analysis showing precipitation statistics for June as well as     December.
 
 June        ![image](https://user-images.githubusercontent.com/91682586/145423227-9b0190b4-0bff-4770-b3ca-39dd1e5c7192.png)   ![image](https://user-images.githubusercontent.com/91682586/145479442-f6f1a810-d72c-471a-8664-ea84e53fe5dc.png)
 
 
 December    ![image](https://user-images.githubusercontent.com/91682586/145423300-95f7448d-73a9-40fc-bca1-4bfb5dbe6e5a.png)   ![image](https://user-images.githubusercontent.com/91682586/145479359-a1c7a4b8-505d-4c68-aa5e-1dbca14f77d3.png)

The histograms show a low overall likelihood of rain with a maximim of precipiation in June of only 4.43 and in December 6.42 respectively. 
These additional queries also support a decision to go ahead with the investment. 

Another way to evaluate the data would be to check the temperatures and rainy days over a whole year or to test if another station nearby gives us similar results. 


