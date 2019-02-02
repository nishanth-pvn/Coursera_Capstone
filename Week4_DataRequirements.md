# Data Requirements

Required data can be gathered from:


- Singapore regions information can be obtained from Wikipedia:  
[Regions of Singapore](https://en.wikipedia.org/wiki/Regions_of_Singapore)
  
  > Inorder to make recommendations on suggested product brands in new retail outlets to be opened, Singapore segmentation will be made       based on different neighborhoods.
  
  > Full list of neighborhoods can be obtained from Wikipedia under Regions of Singapore, but only their names. They must be geolocated       in order to use Foursquare services for obtaining venues.


- For geolocation of neighborhoods _Python geocoder_ will be used. 

  > Geocoder retruns latitude and longitude information for every neighborhood center, then it will be used as main Foursquare input.
  

- In order to obtain top attractions/recreational facilities in each locality we will use [FOURSQUARE](https://foursquare.com/) API.

  > Using services provided by Foursquare we can obtain top outdoor / recreational facilities for every neighborhood. Such services           requires input geolocalization (i.e) latitude and longitude which we obtained in previous step.
