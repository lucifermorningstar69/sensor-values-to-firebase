# sensor-values-to-firebase
sending dth11 sensor values to firebase realtime databse using esp8266.


first create a new project in firebase
dont enable google analytics for this project
go to authentication and create an ananymous auth
then create a realtime database in firebase 
go to project settings and copy the web api id 
in realtime database copy the url present on the top 
paste both of these in the respected place in the code and also enter your ssid and wifi password in the code
DTH11 sensor is connected to D1 in the nodemcu esp8266
dont forget to install the respective libraries used in the code
