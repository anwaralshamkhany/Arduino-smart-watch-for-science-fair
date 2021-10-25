# Arduino-smart-watch-for-science-fair

This wristband is desgined for the elderly where it uses a blood oxygen, heart rate and temperature sensor where when certain parameters are met it has an on board wifi chip and is able to respond to message emergency contacts through the Blynk Platform. It should be noted that the way we masured results throughout the expirement was through the serial monitor and the on board liquid display. However the features to make this system complelty wireless with an esp8266 can be done.

<img width="398" alt="Watch 1" src="https://user-images.githubusercontent.com/81518926/138619350-e9a544b3-ff4f-40b7-9b20-197b7fadc50e.png">


# Materials Needed
1 nodemcu 12E microprocessor                                                                                                                                                     
X5 220k ohm resistors                                                                                                                                                           
1 perma flexible PCB half breadboard size                                                                                                                                       
3 3.5 volt lithium ion button batteries                                                                                                                                         
AB transparent epoxy resin 60A + 20B                                                                                                                                             
1 0.91 inch 128x32 IIC 12C blue OLED display                                                                                                                                     
1 Heart rate with pulse oxygen breakout board for arduino                                                                                                                       
1 button cell battery charger                                                                                                                                                   
1 BMP280 barometric pressure sensor                                                                                                                                             
30 male-to-male jumper wires                                                                                                                                                     
1 step down voltage regulator                                                                                                                                                   
1 soldering iron                                                                                                                                                                 
1 pair of needle nose pliers                                                                                                                                                     
1 fingertip oximeter with digital display                                                                                                                                       
1 blood pressure and heart rate cuff                                                                                                                                             
1 digital ear thermometer                                                                                                                                                       

# Instructions for setup
Begin by cutting of the ends of the male to male jumper wires and use pliers to cut open the leads and solder 2 wires to the SCL and SDA pins. Since we are attaching a variety of sensors we will need to communicate with the arduino over I2C. This means that the Blood oxygen sensor, pressure sensor and Heart rate sensor will be connected in series with the exception of their power and GND pins. The mini display will be soldered on near the end as it goes on top of a couple of the sensors. 
