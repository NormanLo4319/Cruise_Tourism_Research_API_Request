# Cruise Tourism Research API Request
Using the Google Map API and Web-Scripting Tools to collect cruise ports and cruise ships data.  The data can be used for urban economics, economics development, or social economics analysis.

## AISHub API 
AISHub allow its members to access AISHub data, which originally developed as collision avoidance tool that enables commercial vessels to 'see' each other more clearly in any conditions and to improve helmsman's information about the surrounding environment.  

[AISHub API Documentation](https://www.aishub.net/api)

![AISHub](images/AISHub.png)

## Google Maps API
The Google Maps Platform has a wide variety of geo data features.  In this research project, we are using the Google Maps API to match the curise ports geo location to its city. The matched locations will be used to test the hypothesis of the curise tourism effect to the local socio-economic impact.

![GoogleMap](images/GoogleMap.png)

## Wikipedia Data
For indentifying the curise ships capacity for later analysis, we utilized Pandas library to read the html tables from Wikipedia. In this section, the curise ship pessager capacity and crew capacity are extracted and saved into a csv file.

### Cruise Ship List
![Cruise List](images/cruise_list.png)

### Cruise Ship Capacity
![Cruise_Capacity](images/cruise_capacity.png)
