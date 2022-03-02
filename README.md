# NYC_Citibike_Challenge

## Overview  
Rentable "Citi Bikes" have been deployed in New York. The porpose of this analysis  
is to explore the data to determine the viability of this same system in Des Moines.  
Tableau, Puthon, and Jupyter will be used to visualize the data using various  
methods below.  

## Results  
First I sorted the data by age and trip duration.  
![Trip_Duration_By_Age](https://user-images.githubusercontent.com/91306342/156315318-4b7b0f3b-c958-4c55-8e87-aa742644d1d8.PNG)

Then created two pie charts displaying Customer Type and Gender.  
![Pie_Charts_Gender_and_CustomerType](https://user-images.githubusercontent.com/91306342/156315710-347bfbae-c0c4-4ba8-8202-4c6c1fdf564c.PNG)  

The top starting locations are best displayed by a bubble map:  
![Starting_Locations_BubbleMap](https://user-images.githubusercontent.com/91306342/156318656-40a30679-5e42-4a19-bd66-56a2b4188277.PNG)  

Some takeaways from the above were about two-thirds of the customers  
were male and over 80% of them were subscribers to the Citi Bike service.  

Rental time by gender expands on the related pie chart above.  
![Rental_Time_By_Gender](https://user-images.githubusercontent.com/91306342/156317605-acecd14b-30d8-4fc3-b41a-cc4c45393844.PNG)  
A vast majority of rentals ended within 20 minutes, and almost  
no rentals lasted more than 50 minutes.  
The lines have a very similar curve, but the one representing  
males was scaled higher due to higher participation rates.  

Trips by Weekday visualized using an hourly heatmap yielded the following:  
![Trips_by_Weekday_Per_Hour](https://user-images.githubusercontent.com/91306342/156320019-411828b4-26df-4653-ab48-ce0b8d64b0e3.PNG)  
These results represent data that is expected of a metropolitan area.  
Usage spikes before and after work hours on weekdays, and on weekends  
usage is heavy in the afternoon, with more on Saturday than Sunday.  

I then separated the heatmaps by gender:  
![image](https://user-images.githubusercontent.com/91306342/156321243-d083b1c2-e920-4464-b80c-992cfc30f306.png)  
The weekly patterns are similar between the genders.  

When sorting by weekday similar patterns between the genders were also observed:  
![Heat_by_Weekday_and_Gender](https://user-images.githubusercontent.com/91306342/156322148-d8a1220f-3945-452a-a231-6ee513f291d4.PNG)  

## Summary  

The above visualizations seem typical of a major metropolitan area.  
There were two observations that caught my eye: the usage spike by   
customers born in 1968 and the lack of a usage spike on Wednesday  
evenings.  

![Summary_Wednesday](https://user-images.githubusercontent.com/91306342/156326060-d497d10b-75cf-49b1-a0c7-db88a7d7cdf8.PNG)

When viewing a more granular chart of Age and birth year, it becomes  
apparent there is likely bad data the further back the birth year, as  
it is unlikely there are so many users aged 80+ and even 100+. The spike  
in 1968 still needs to be further investigated.  

![Trip_Duration_by_Age_Summary](https://user-images.githubusercontent.com/91306342/156324787-dddae53c-5a63-4211-b62a-db3bfb584738.PNG)

