# ZipCode Clock

This is a zipcode clock I created for my Networked Media class. I used zipcodes from both the US and Mexico and used census data from both countries to collect the zipcodes and their coordinates, After this, I used leaflet, a free map api, and some javascript to connect my zipcodes to my clock. The way the clock works is it takes the time and searches through an array containing zipcodes and coordinates, if it finds a match it displays the zipcode that matches the time. I also added in perameters so that if the time is longer than 5 digits, it searches for the last 5 digits in the zipcode. For example if the time is 12:34:21 the code will search for the zipcode 23421.

## Sources

[string to number javascript](https://www.freecodecamp.org/news/how-to-convert-a-string-to-a-number-in-javascript/)

[leaflet documentation](https://leafletjs.com/)
