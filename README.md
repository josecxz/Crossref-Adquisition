# Crossref-Adquisition
Python code to get data from Crossref based on DOI pre-prints

To extract the data we use Python to query the information of the pre-prints by using the public API provided by Crossref. 
We used some usefull libraries to query our data: 
- Habanero: Used to query throught the Crossref API
- Pandas: Used to create an excel document

The code we use is uploaded in this repository in two scripts, "Crossref_data" and "Crossref_data_dates". The first one allow us to get all the reference count and the relation of the pre-print, while the second script allow us to filter the creation date of the pre-print. Both scripts generates an excel document that allows us to process all the data. 
