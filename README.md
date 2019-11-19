# Cruise_Tourism_Research_API_Request
Using the Google Map API and Web-Scripting Tools to collect cruise ports and cruise ships data.

## AISHub API 
AISHub allow its members to access AISHub data, which originally developed as collision avoidance tool that enables commercial vessels to 'see' each other more clearly in any conditions and to improve helmsman's information about the surrounding environment.  

[AISHub API Documentation](https://www.aishub.net/api)

## Google Maps API
The Google Maps Platform has a wide variety of geo data features.  In this research project, we are using the Google Maps API to match the curise ports geo location to its city. The matched locations will be used to test the hypothesis of the curise tourism effect to the local socio-economic impact.

## Wikipedia Data
For indentifying the curise ships capacity for later analysis, we utilized Pandas library to read the html tables from Wikipedia. In this section, the curise ship pessager capacity and crew capacity are extracted and saved into a csv file.
