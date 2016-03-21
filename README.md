# opendataportals

A collection of Australian open data portals published by ODI Queensland.

 - The data is presented using TablePress on the [ODI Queensland site](http://queensland.theodi.org/home/resources/data/).
 - A variation of the data with the policy link removed and location added is held in a Google Sheet.
 - A CSV file has been exported from the Google Sheet and is stored in this respository
 - A JSON Table Schema describes the structure of the data
 - A Data Package, that includes the JSON Table Schema, describes the CSV
 - A competing metadata scheme, [CSV on the Web](https://www.w3.org/standards/techs/csv#w3c_all) by W3C, also describes the CSV
  - csv-metadata.json is generated using the [CSV Metadata Editor](http://data.wu.ac.at/csvengine/csvm/editor) from Vienna University and then hand edited to add restrictions
  - australian-open-data-portals.csv-metadata.json is the original hand edited file before the above generator was discovered.
 
Suggestions, questions and pull requests are welcome either here or via the [ODI Queensland web site](http://queensland.theodi.org/home/contact-us/).
