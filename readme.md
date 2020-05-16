# 2020 Baltimore City Building EUI Analysis with ST & LT ROI

## Summary 
Baltimore City is one of the more efficient cities in the nation, however bleeds money in inefficient energy use in many building spaces. Areas of focus are amongst the police department, warehouse and storage spaces as well as museums. Solutions with quick 2-3 yr ROI are to invest in high speed doors in warehouses and energy saving lighting controls and long term solutions are to retrofit Heat Mirror windows in high EUI spaces which are buildings 50+ years in age.  

## Problem Statement
How energy efficient are Baltimore city buildings split by size, sector, and age and of the buildings under Baltimore City control, what measures can be taken to create energy-efficient solutions? 

## Background and Motivation
Baltimore City DGS is interested for three reasons. One, efficiency, fiscally, and sustainability. In FY19 Baltimore City spent 19M on utilities and found that buildings made up the largest amount of energy consumption. The goal is to reduce the spend on energy as well as decrease the carbon footprint. 

## Geospatial Analysis
The first analysis we conducted here was a simple heat map visualization of the 2019 Source EUI for Baltimore buildings, overlaid with council district boundaries. The resulting visualization is displayed below. The main takeaway here is that council districts 11 and 12 have the highest reported Source EUI in 2019. This is self-explanatory as the Downtown/Inner Harbor region contains the highest density of DGS owned and operated buildings as well as the greatest population density with regards to workforce. As such, this was a good logic check to better inform our analysis down the line.

![](https://github.com/bdmello1/BaltimoreCityDGS_EUI_efficiency/blob/master/Images/Screen%20Shot%202020-05-15%20at%2010.26.27%20PM.png)

During the data cleaning and analysis process, one key metric we wanted to calculate was the percent change in source and site EUI from 2017 to 2019. One thing to note here is that only half of the fiscal year’s data was available for the 2017 and 2019 fiscal years. As such, it is important to take these results with a grain of salt. Looking at all the buildings in Baltimore, only one building demonstrated a positive percent change in Source EUI, meaning that it was the only building whose source EUI increased over the three fiscal years. This was the Baltimore City Police Department in the Northwestern District. Amongst all the police departments in Baltimore City, this was the only one which shows an increase in Source EUI. Coincidentally, this is also the largest police department in Baltimore City by square footage. The interesting thing here was that in terms of raw Source EUI, this department showed among the lowest. However, it is still important to understand why the Source EUI has increased by almost 20%.

![](https://github.com/bdmello1/BaltimoreCityDGS_EUI_efficiency/blob/master/Images/Screen%20Shot%202020-05-15%20at%2010.26.38%20PM.png)

At the same time, we also wanted to take a look at Site EUI percent change. Aside from the previously mentioned police department, only 2 other buildings demonstrate a positive change in Source EUI from 2017 to 2019. First is the Carroll Mansion Museum. This was built in 1812, so the increase in EUI could simply result from needing to update the HVAC unit on site. The other building is the Eastside Career Center. The percent change here is not large, but still it is something to consider as the building was only built in 1955. It is also important to note that almost all buildings built after 1970 have a negative change in Source and Site EUI, so they are definitely doing something right. 

![](https://github.com/bdmello1/BaltimoreCityDGS_EUI_efficiency/blob/master/Images/Screen%20Shot%202020-05-15%20at%2010.26.49%20PM.png)



Our Executive Report details the rest of our analysis and recommendations.

