#**_Geolocation_**

##Author: **BO LIAO**
###Date:_Jan 30th, 2015_

##Description - general description of the project
1. The webpage was built to check to see if the user's current browser supports the navigator.geolocation object.      
 If the browser does not support geolocation then the page displays an feedback message to the user.
2. If geolocation is supported then the user's current location is fetched in as a static google map.


##Instructions - how to use the app / site, how the code works.
1. If geolocation is supported then the user's current location is fetched in.
2. A Canvas element is created and append it to the page.
3. The Canvas will only be added to the page IF the browser supports geolocation.
4. A google static map is loaded into the canvas element;
5. The google static map includes a marker at the center of the map, and     
 The map image is loaded at zoom level 14.  
 The map image size is 400px by 400px.   
 This is the link to [Google map API](https://developers.google.com/maps/documentation/staticmaps "Links to an external site") 
