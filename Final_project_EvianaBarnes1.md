# Outline  

## Project Summary
I will be constructing visualizations that tell the story of the limits of internet access in West Virginia for my final project. Through my deliverables, I would like to inform viewers on how the lack of internet access affects the lives of West Virginians. 

I will be creating visualizations using county-level census data from West Virginia and nationwide. I have collected data on the number of households in West Virginia without internet access and the total number of households in each county in West Virginia. Using these variables, I calculated the proportion of households in each West Virginian county that do not have internet access. I found it important to calculate this percentage because if we solely look at the number of households, then more populous counties would seem to have the worst internet access. I think that by instead showing these as a percentage, it’s easier for viewers to conceptualize what it would be like to live in an area where one in five households lack internet access. From these percentages, I used an “if” function in excel to find how many counties in West Virginia have more than 20% of households lacking internet access. 22 of West Virginia’s 55 counties fell into this category. 

I decided to pull the same data at a national level to make comparison easy for my viewers. I pulled each county’s internet access data by household nationwide and each number of households by county nationwide. From here I calculated the percentage of households lacking internet access nationwide, then ran the same “if” function to calculate the number of counties nationwide with over 20% of their households lacking internet access. There are 3,152 counties in the US. Census data shows that 855 of these counties have over 20% of households lacking internet access. This means that 27% of counties nationwide (855/3,152) have more than 20% of their households lacking internet access. In West Virginia, 40% of counties (22/55) have more than 20% of their households lacking internet access. 

I think it would be fruitful for my final project to find a national ranking of state-level households without internet access and see how West Virginia compares. If I can’t find this data specifically, I think I could dig into the data I already have to calculate this myself. 


## Project Structure

I believe it would be most impactful for my project to start at a national level of data then move in to West Virginia level data. I would start with the data nationwide showing where internet access is lacking. This could be depicted through a US map and utilizing color to show counties that have more than 20% of their households lacking internet data. Then I will zoom in to West Virginia. I will keep the color scheme the same so the viewer can immediately comprehend that they are being presented with the same data but zoomed in to state-level. I think that from here it would be fruitful to utilize a table showing how West Virginia compares nationally. The next section of my presentation could emphasize what this means for West Virginians – what does life look like when one in five families in your community do not have internet access? This tells the audience why it is important to expand internet access in West Virginia. My last section will be a call to action. I am going to do more research on broadband expansion efforts to see what other advocates have been promoting. Another call to action I could try would be by informing viewers on what current political candidates have broadband expansion as a priority to them.

## Initial sketches

The first image in my story is a US map with data on levels of internet access by county with nationwide data. 

**Header**: Percent of Households without Internet Access in the US by County
![Visualization 1](https://github.com/evianambarnes/portfolio/assets/156966766/8145311d-3115-4988-ae2f-f0095dacb782)

Then I will keep everything the same for my second visualization, except the only color of the visualization will be counties with over 20% of households lacking internet access. I may also add in a text box on this visualization about the states or areas with the least access to internet.

**Header**: Counties in the US with More Than 20% of Households Lacking Internet Access
![Visualization 2](https://github.com/evianambarnes/portfolio/assets/156966766/17f36ceb-1cb6-4bc8-8a7c-b84acab63c4c)

Then we will move to West Virginia level data. I will use the same colors, but update the scale bar.

**Header**: Percent of Households without Internet Access in West Virginia by County
![Visualization 3](https://github.com/evianambarnes/portfolio/assets/156966766/b79ab5ff-50e8-41ba-9048-1a5f50b1c292)

Next I will create either a dashboard or table of a sort to show how West Virginia compares nationally by the number. I will emphasize that 40% of counties in West Virginia have more than 1/5 households without internet access. Nationwide, only 27% of counties have more than 1/5 households without internet access. 

The last part of my story is a call to action. I don't think a major visualization is necessary here. Rather, I think hyperlinks to resources supporting broadband advocacy is more impactful.



# The data

My data is pulled from census data collected between 2019 and 2021. I have found data on number of households in each county in West Virginia, number of households without internet access in each county in West Virginia, number of households in each county nationwide, and number of households without internet access in each county nationwide. Additionally, I found how internet access in West Virginia has increased over the last five years. I'm not sure if I will need this last piece of data, but I figured it would be good to have it on hand for now. I plan on using the data to create a map of the US that utilizes a color scheme that shows where internet access is lacking. Then I would like to create a map of West Virginia using the same method and medium. I might end the story with how internet access has been increasing in West Virginia over time. I will be finishing the story with a call to action. I still need to research broadband advocacy initiatives to find opportunities best tailored for my mission and audience.


| Name | URL | Description |
|------|-----|-------------|
|Households|[Link to Data](https://www.datacommons.org/tools/visualization#visType%3Dmap%26place%3DgeoId%2F54%26placeType%3DCounty%26sv%3D%7B%22dcid%22%3A%22Count_Household%22%7D)|Count of West Virginia Households by County|
|Count of Households: No Internet Access|[Link to Data](https://www.datacommons.org/tools/visualization#visType%3Dmap%26place%3DgeoId%2F54%26placeType%3DCounty%26sv%3D%7B%22dcid%22%3A%22Count_Household_NoInternetAccess%22%7D)|Count of West Virginia Households without Internet Access by County|
|      |     |Count of Nationwide Households by County|
|      |     |Count of Nationwide Households without Internet Access by County|
|Count of Household: No Internet Access|[Link to Data](https://www.datacommons.org/tools/visualization#visType%3Dtimeline%26place%3DgeoId%2F54%26sv%3D%7B%22dcid%22%3A%22Count_Household_NoInternetAccess%22%7D)|Count of WV Households without Internet Access 2017-2021|

# Method and medium

I believe my data and mission would be best visualized through Shorthand, Tableau, and ArcGIS. I’m not sure yet if I will need to use ArcGIS and may be able to complete the visualizations in tableau. But I figure I will play around with both Tableau and ArcGIS for my visualizations, since my final deliverable is likely to include maps. My initial vision for the project would include a nationwide map of internet access, a map of West Virginia’s internet access, and some dashboards or tables to drive the point of the maps home. I will be embedding the visualizations into a shorthand page as the final full deliverable.
