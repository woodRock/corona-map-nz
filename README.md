# corona-map-nz
Corona virus cases by city for NZ. A script that automatically updates the data.
The map can be found [here](https://woodrock.tk/#/corona)

# Preview
![corona-map-preview](https://imgur.com/NdPDKYh.png)

## Script
The bash script reads data from a url and extracts the frequency of cases for each of the cities listed. 
This information is stored in a csv file, which also has the GIS data for each of the cities. 

## Map
The CSV can then be uploaded to mymaps. This is an extension of Google Maps that allows us to create our own layers.
1. Upload the CSV 
2. Set the label to City
3. Style the layer to a range by cases 
4. Change the icon to Biohazard 

## Source
Ministry of Health [data](https://www.health.govt.nz/our-work/diseases-and-conditions/covid-19-novel-coronavirus/covid-19-current-cases)

## Update (26/03/20)
The ministry of health have now created there own maps on the original data-source. Therefore the development of this map has been made redundant. It will still be kept up to date. However, new features will not be added.
