1. Convert KML to GeoJSON (for LineString data,which has only sample trees)
Open kmltogeosjson.html in your browser. This will convert your KML file to GeoJSON format.
Copy the GeoJSON data provided and save it as anything.geojson (you can name the file as you prefer).

2. Convert LineString GeoJSON to Polygon(Use this to get the site geojson which is supported by webapp)
Open geojsontosite.html in your browser and paste the LineString GeoJSON to convert it to a Polygon format.
Copy the newly converted GeoJSON data and save it as a new file.

3. Convert GeoJSON to Sample Trees Location(This is for importing sampleTrees as csv on webapp)  
Use convertGeoJSONtoSampletrees.html to convert your GeoJSON file (from step 1) into a CSV file.
Open the resulting CSV file in Excel or Google Sheets.

4. Format and Clean up the CSV File 
Adjust the CSV file according to the format specified in this Google Sheets template: Format Template.
https://docs.google.com/spreadsheets/d/1b7CulH4HAqDWPEVbnTHa-04MkymDKc7XuyHvQxdwfmk/edit?gid=1358388445#gid=1358388445

5. Clean Up the CSV File(You can try this tool to convert required filed)
Create a tool using chatGPT to tranform you data to required format.Please ensure you only have fields that are mentioned in the sampel csv. Once done dowload it.

6. Import the CSV File(The cleanup one)
Finally, import the formatted CSV file into the TreeMapper Beta web application.
