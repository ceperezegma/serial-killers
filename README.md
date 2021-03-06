# serial-killers

**Project killR:** Data on both male and female international serial killers and scripts for scraping, preprocessing, and analyzing data on serial killers.

## Description: serial_killers_data

Contains the following scraped data on both male and female international serial killers (N = 576):

* name (full, given, and surnames)
* pseudonym *(note: pseudonyms are partially in German)*
* country
* sex
* victims (proven, suspected)
* years active (active from-to, active from, active to)
* geocoded country locations (longitude, latitude)

Data source: https://de.wikipedia.org/wiki/Liste_von_Serienmördern

## Description: serial_killers_analysis

The script covers

* scraping Wikipedia tables containing information on international serial killers
* wrangling scraped data
* geocoding the killers' locations by country using Google Maps API
* mapping the killers' locations as both points and polygons with *leaflet* and *ggplot2*
  
using the abovementioned data set on N = 576 serial killers.  

## Description: Serial_killers_US

The script covers

* scraping a Wikipedia table containing information on US serial killers
* wrangling scraped data
* scraping a Wikipedia table containing US states and extracting information on the killers' locations from strings
* predicting the killers' sex based on their given names using *gender* and *genderdata*
* scraping a Wikipedia table containing causes of death and extracting information on the killers' causes of death from strings
* visualizing the killers' causes of death, number of victims, and sex
* mapping the killers' locations

using the example of serial killers in the US. 
