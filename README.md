# Tornados
Visualization program for tornado events from 2000 to 2018<br>
Database Link: [here](https://www.ncdc.noaa.gov/stormevents/)

## Libraries Used
Bootstrap - UI<br>
JQuery - DOM Manipulation<br>
D3 - Visualization of Data

## Video
[![Thumbnail not found](/Screenshots/Thumbnail.png?raw=true)](https://youtu.be/BS6PQjrhPI0)

## Project Link ----> [here](https://davidcooper1.github.io/Tornados/)
## About the Data
The data used in this visualization was derived from the NOAA's NWS Storm Event Database. It contains vast information on various storm events since 1950. However, for the purposes of this project, only number of tornados and damage caused from month to month was necessary. In processing each file, the count and damages of tornados was tallied up for each state on a monthly basis. The end goal was to trim off unneccessary data and discard other events. Although I was not able to implement the ability to display damage in the graphs, the data still exists in the file created by pre-processing.

## Findings
While displaying the data I found that the data spiked up in two places, April 2011 and May 2015. In researching the spikes further, it appears that the first major spike, happening in Alabama, Tennessee, and Mississippi, was due to a super outbreak. In fact, the NOAA called it "one of the deadliest and most expensive meteorological disasters on record." [[1]](https://www.ncei.noaa.gov/news/2011-tornado-super-outbreak) The second spike, happening in Texas and Oklahoma, was stated by the NOAA as being the "most active tornado month since April 2011". [[2]](https://www.ncdc.noaa.gov/sotc/tornadoes/201505)

### April 2011 Outbreak
![Image Not Found](/Screenshots/April2011.png?raw=true)

### May 2015
![Image Not Found](/Screenshots/May2015.png?raw=true)

## References

[1.) https://www.ncei.noaa.gov/news/2011-tornado-super-outbreak](https://www.ncei.noaa.gov/news/2011-tornado-super-outbreak)<br>
[2.) https://www.ncdc.noaa.gov/sotc/tornadoes/201505](https://www.ncdc.noaa.gov/sotc/tornadoes/201505)
