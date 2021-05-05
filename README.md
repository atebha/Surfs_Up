# Surfs_Up

Purpose:

  Using Python, Pandas, Numpy, and SQLAlchemy to perform an analysis of Oahu temperatures to support the opening a surf and ice cream shop venture. A dataset comprised of Oahu weather station temperature and precipitation readings for 2010 through 2017 was used to review temperature data for two particular months, June and December. Both June and December were analyzed for every year in the dataset. 
  
  
Analysis:

  The temperature for the area remains rather consistent throughout the year. Both observed months nearly have the same number of data points and nearly identical values. The december data set though did have slightly less recorded values whihc may attribute to the standard deviation being higher. There main key differences that were evident were the following:
  
    - The June recorded data points were more, almost 200 more entires, this clearly impacted the standard deviation compared to December's recorded dataset. 

    - The IQR for June was 4 and more consistent with the standard deviation than December which had a IQR of 5. This indicates the June set was more normalized data compared to December. 

    - Both months observaed were fairly close in temperatures recorded, this indicates that weather would be a minimal impact on this ice cream venture proceeding forward. 

Challenges:

  The only challenged was setting up Flask.
  
  
  Summary:
  
    The weather for this area is failrly consistent regardless of season. The investor's concern of weather being an impact should be resolved based on the data set reviewed. Demand however may not be contigent upon weather and more likely tied to other factors such as travel pricing, global pandemics, economic stability for developed nations. Additoinal queries for the data set could be as follows:
    
     - Analyze rainfall for the given months on a daily record basis. Rainfall may indicate poorer weather that would impact demand to go out and eat ice cream while surfing. 
     - The dataset should be expanded to look at years beyond 2017 as climate change is becoming more icrementally impactful. This makes historical data less accruate and more prone to drift, leading to less predictive accuracy. 
