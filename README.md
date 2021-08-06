# Shield-ESP8266-4Relay
In college, I had the opportunity to work in a design of an IoT system. 

The project was quite simple: mechanics students wanted to use the 3D printers that were in the classroom. from the comfort of their house. It's very usual that they spend hours designing some mechanism in AutoCAD or equivalent, and then they spend hours waiting for the 3D printer to finish the job. To accelerate this process, they wanted to upload the files to the 3D printers and turn on the 3D printers at any given time and start printing, so when they arrive at the classroom the next day, the printing was finished.

My job was to use a relay to control the power for the 3D printers, using the popular ESP8266. So, I designed a PCB shield, that lies between the ESP8266 and a 4 relay board, as you can see in the images, the PCB is quite simple. 
Although the "abstraction" of the PCB was quite hard because I had to think which part is going up/down and in which order. Once done, the PCB design was quite easy. 

The software was made in Arduino IDE using C, and the ESP8266 connected to a dashboard in Ubidots(cloud). Using a button, the user was able to turn on/off the 3D printer.

For the prototype of the board, I use the same process that was explained in my other repository: Excellon_to_Gcode.
