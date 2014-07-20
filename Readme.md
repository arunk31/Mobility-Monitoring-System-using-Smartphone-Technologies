Mobility-Monitoring-System-using-Smartphone-Technologies
========================================================

This project is used basically for monitoring purpose. It has two modules:  
1) Mobile Application* 
2) Web Application  

The Mobile Application has the following functionalities: 

-Collect the users location data from GPS sensor at specific interval and store it in remote database
-Show the user location on Google Maps with in the application with a geo-fence area to which the users mobility is limited
-Alert the user when this geo-fence is crossed also the admin via a SMS from users mobile
-Register with web application for receiving notification messages from admin via GCM  

The Web Application has the following functionalities: 

-Admin can view the location data of the users(current/previous/the location travelled beyond geo-fence) and locate it on Google Map on a single click also individual users data can also be viewed
-Admin can send Notification messages to the registered devices on demand via GCM

*App is available for Android platform
