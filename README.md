# Extreme Weather
### Project Title:
    Extreme_Weather
### Team Members:
    Angela Thompson
    Elizabeth Sanchez
    Jacob de Vries
    Chia Sun
### Project Description/Outline: *similar to thesis statement*
    Our project is to determine patterns in wildfire events in the state of California. 
We'll examine relationships between frequency of these events and the economic impact 
through census data. Our data will be analyzed and segmented into counties and by years; 
trend of any economic changes surrounding wildfire events location and time. 
    * Heatmap for wildfires per county, hover icon options
### Research Questions to Answer:
    * Possible drought correlation with wildfires
    * Population comparison and extreme weather events (extreme cold in less populated area vs more populated?)
    * California severe weather events, could then compare with other states
    * Comparing income level (poverty level) to economic impact of severe weather events
    * Crop and property damage comparison for counties for high or most severe weather events
### Datasets to Be Used:
* https://www.ncei.noaa.gov/support/access-data-service-api-user-documentation
* census
* pooossibly google maps one
* weather api 
### Considerations to Remember:
* Consistent format - if using two different weather data sets, need to ensure that all have the same format
* County ID - uses FIPs, could be different between NOAA dataset vs Census dataset. Looks like
{'for': 'county:*} --> have to make find this function to make sure it uses FIPS
### Rough Breakdown of Tasks:
Before 2/3
Figure out which data we want from the census api, then determine which csv or what specific files we would want to use in exlporation. 
Then we can determine how we want to clean the data and which portions to specifically to use. After data cleaning we can then partition out 
questions and diving into answering our analysis questions. 
* Exploration
    Everyone explore the data and which portions we want to use in our analysis
* Cleaning
    
* Analysis
### Weather Types: 
* Wildfires (2010 - 2019)
    * drought
    * frequency vs pop.
    * economic impact vs. pop.
    * poverty level vs frequency
