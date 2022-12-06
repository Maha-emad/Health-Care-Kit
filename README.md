# Health-Care-Kit 
We have designed a special wireless-controlled device that helps people with chronic diseases as  measures body temperature, pulse rate and oxygen percentage which considered as the common risk factors for any disease, so we try to make their measurement as simple and easy as possible in order to help you be more aware of your health. 

The reading are appeared either on the LCD fixed on the divice or on a mobile application to make it be more readable and to be able to store them for further analysis .

Used plateform : arduino IDE  

Used components : 
1-Bluetooth Module (HC-05)                                   .
2- Monitor (16*2)                    
3-Temperature Sensor (LM35)                                    
4-Potentiometer   
5-Pulse Oximeter Sensor                                      
6-3 Resistances (4.7 k ohm)  

![Screenshot (152)](https://user-images.githubusercontent.com/71048834/205670335-0bbf0481-4fc0-4df3-b2a5-a199cddb6617.png)


wiring instruction:
-	LCD monitor pin Vss – Arduino pin GND 
-	LCD monitor pin VDD – Arduino pin VCC (5v)
-	LCD monitor pin VO – Potentiometer pin 2
-	LCD monitor pin RS – Arduino pin 9 
-	LCD monitor pin RW – Arduino pin GND
-	LCD monitor pin E – Arduino pin 8 
-	LCD monitor pin D4 – Arduino pin 7
-	LCD monitor pin D5 – Arduino pin 5
-	LCD monitor pin D6 – Arduino pin 6
-	LCD monitor pin D7 – Arduino pin 4
-	LCD monitor pin A – Arduino pin VCC (5v)
-	LCD monitor pin K – Arduino pin GND
-	Potentiometer pin VCC – Arduino pin VCC (5v) 
-	Potentiometer pin GND – Arduino pin GND 
-	Bluetooth Module (HC-05) pin RXD – Arduino pin 1 
-	Bluetooth Module (HC-05) pin TXD – Arduino pin 0 
-	Bluetooth Module (HC-05) pin GND – Arduino pin GND 
-	Bluetooth Module (HC-05) pin VCC – Arduino pin VCC (5v) 
-	Pulse Oximeter pin VIN – Arduino pin VCC (5v)
-	Pulse Oximeter pin SCL – Arduino pin SCL
-	Pulse Oximeter pin SDA – Arduino pin SDA
-	Pulse Oximeter pin INT – Arduino pin 2
-	Pulse Oximeter pin GND – Arduino pin GND 
-	Temperature Sensor (LM35) pin VCC – Arduino pin VCC (5v) 
-	Temperature Sensor (LM35) pin Vout – Arduino pin A0 
-	Temperature Sensor (LM35) pin GND– Arduino pin GND  
![Screenshot (150)](https://user-images.githubusercontent.com/71048834/205670807-a2f489a9-bb53-4c6b-9693-d0512784558d.png)


