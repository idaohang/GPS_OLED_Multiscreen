### Arduino MICRO / OLED GPS Inforamtion

This Arduino sketch combines the use of an Arduino Micro, Adafruit's GPSv3, and 128x64
OLED. The sketch provides the ability to cycle thru multiple screens on the OLED 
display. Screens include a simple Speed (MPH), UTC time, and finally a comprehensive
display of the GPS complete information formatted for display. Displayed information
includes received GPS time, date, location, satellites in view and antenna status.

Note: By default this sketch uses the Leonardo/ Micro's serial UART Serial1. Provisions are included to easily modify the sketch to use software serial. 

--brycej
