# Retail-Store-Location-Scraper
 Using web scraping techniques(such as requests and BeautifulSoup) to extract the store locations, store name, address, timings, coordinates(latitude/longitude), and phone number from the website.


INTRODUCTION


This Python script is written to extract data from the Spencers 
retail brand website in India. The script utilized the “requests”
and “BeautifulSoup” libraries to extract the store information 
such as store name, address, postal code, locality, region, contact 
information, and working hours.


APPROACH


The script used a loop to create a list of full addresses by 
concatenating the individual address components extracted from 
the webpage. The script then used an API from Trueway 
Geocoding to extract the latitude and longitude coordinates of 
each store address. The Trueway Geocoding API requires an API 
key and uses the RapidAPI platform for authentication.
Finally, the script created a list of dictionaries to store the data 
and wrote it into a CSV file using the “csv” library.


 Challenges



The main challenge faced while writing the script was in 
extracting the full address of each store, as the address 
components were in different HTML tags. However, this was 
PAGE 2
resolved by concatenating the different components into a single 
string.
Another challenge faces was getting the latitude and longitude of
the locations. However using API from Trueway Geocoding from
the RapiAPI platform to extract the latitude and longitude 
coordinates of each store address resolved the problem.
Overall, the script was successful in extracting the desired data 
and storing it in a CSV file
