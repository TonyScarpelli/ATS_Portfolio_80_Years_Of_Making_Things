---
title: Making electronic things
publishDate: 2024-02-07
img: /assets/Electronics/ArduinoTachometer.jpg
img_alt: Lathe tachometer
description: ""
tags:
  - Design
  - Electronics
---

When I was around 6 years old, my father showed me the crystal radio he had built. I was fascinated on how it worked. Then when I was older I built a one tube radio I wanted for my birthday. That led me into electronics.

The picture above shows a tachometer that I built for my lathe. It has an Arduino Nano in it and a two line display. As the lathe spindle turns, a wheel on the end also turns. It has a white patch on it. The InfraRed sensor transmits an IR signal, and then reflected to the IR receiver. The signal is processed, and then the rotation speed is displayed.<br><br>

![Lathe](/assets/Electronics/RemoteThermometer1.JPG)
One of the more complicated things you make in the Arduino learning process is a remote thermometer. Here there is the Arduino Uno, the green board on the left, an ESP32 remote transmitter, and an ESP32 local receiver.<br><br>

![RemoteThermometer2](/assets/Electronics/RemoteThermometer2.JPG)
And here you see the Humidity and Temperature on the display. When the project works, you package it up.<br><br>

![Timer2](/assets/Electronics/Timer2.JPG)
What you see above is a tea timer. When you turn it over so that the picture sands flow down, it starts the timer and beeps after the 3 minutes are up. If you don't turn it over it will keep on beeping at you, warning you it's time to fix that tea, get a move on.<br><br>

![Timer](/assets/Electronics/Timer1.JPG)
How it works is there is a mercury switch in it which turns the current on. The microprocessor, the blue thing on the right is an Arduino Nano. Now this is a really small computer.<br>
See  <https://www.arduino.cc/en/hardware> for a list of different Arduino devices.<br>
You program the Arduino microprocessor with a variant of the C++ language. It's so much fun programming these guys.<br>
There is a special programming environment called a UI (User Interface) that's easy to set up and easy to use to help program these things.<br><br>

![DryerDone2](/assets/Electronics/DryerDone2.JPG)
The thing you see above is what I call a "Dryer Done" device. Our dryer is in the basement and has no alarm on it. You place this on the dryer and the vibrations keep a vibrations sensor moving in the device. The legs have feet of magnets to stick to the metal top of the dryer, after all we don't want it to wonder off. When the dryer stops, it calls your phone. Cute, huh?<br><br>

![LawnMower](/assets/Electronics/LawnMower.JPG)
Now this thing is an ongoing project. It's for cutting my lawn automatically.<br>
It uses three ultrasonic sensors, a Raspberry Pi, two motors and two motor controllers, and a lead acid battery.<br>
The mowing part I still have to put together. The design is currently in limbo. I still have to get the gas lawn mower out. This is still on my ToDo list<br><br>

![WateringDevice1](/assets/Electronics/WateringDevice1.JPG)
This thing above is my plant automatic watering device in its development stage.<br>
The blue thing on the right is an Arduino Uno. There are relays to control the water and the moisture sensors, and transistors to control them. The sensors are in a window planter. When the moister level is at the low point, the relays operate some water valves (below).<br><br>

![WateringDevice2](/assets/Electronics/WateringDevice2.JPG)

![WateringDevice3](/assets/Electronics/WateringDevice3.JPG)
The gallon of water here is the source to the valves above.<br>
I've grown basil at least three years this way.<br><br>

![WeatherStation5](/assets/Electronics/WeatherStation5.JPG)<br>
Believe it or not, this is circuitry for a weather station. I bought all the parts and I had to put them together and then add my own programming for it. It uses two "ESP32 Now" microprocessors.<br><br>

![WeatherStation6](/assets/Electronics/WeatherStation6.JPG)<br>
Here you see a fan blowing air onto the anenometer that measures wind speed. I bought a small wind speed meter to ensure accuracy in my calculations. There is also the wind direction sensor, and the rain gauge. What isn't here is the Thermometer (temperature), the Barometer (pressure), and the Hygrometer (humidity) sensors, they are in a different box.<br><br>

![WeatherStation1](/assets/Electronics/WeatherStation1.JPG)<br>
Here is the station on my shed.<br><br>

![WeatherStation2](/assets/Electronics/WeatherStation2.JPG)<br>
This box contains the sensors for temperature, humidity and pressure. There is a screen on the bottom that opens to the atmosphere; the screen keeps the insects out.<br><br>

![WeatherStation3](/assets/Electronics/WeatherStation3.JPG)<br>
This is the transmitter in the shed. It sends a signal to a receiver in my work shop. The signal is broken down into all the values and can either be recorded on an SD memory card for future reports, shown on a LCD display, or viewed in a web browser anywhere in the house.<br><br>

![HeartMonitor1](/assets/Electronics/HeartMonitor1.JPG)<br>
Above is a heart monitor. I have heart problems, so I can see what's going on. I did work in the Maine Medical Center's Cardiology department one year, so I know what all the bad signals look like.<br><br>

![Hawk](/assets/Electronics/Hawk.JPG)<br>
And finally this is a hawk that moves back and forth. Nearby is my Almond tree. Most of the time at the end of August into September when the almonds are almost ripe the birds and squirrels remove them all from the tree. This moving hawk actually kept the birds and squirrels away until the motor burned out. Before I was able to get a more powerful motor, the squirrels saw that it didn't move and took a chance and managed to remove the almonds. Squirrels aren't dumb.<br><br>

The Arduino and all its buddies are very versatile. I have three whole directories just crammed full of projects I've done over the years. If you get a chance, please try one of the Arduino, ESP32 or ESP8266 devices out.

For example this is just a very short, short list of the multi-hundreds of Arduino, ESP32, and ESP8266 files I've tried and created:

LCD_Tachometer.ino<br>
OpticalTachometerOledDisplay.ino<br>
tachometer-using-arduino.ino<br>
Adafruit_Display_Test.ino<br>
AI_Bluetooth_To_Phone.ino<br>
AI_WiFi_PS_Controller.ino<br>
AI_WiFi_Scanner.ino<br>
BLE_Scan.ino<br>
BLE_Server.ino<br>
Blink_LED.ino<br>
Bluetooth_Low_Energy_send_data_to_phone.ino<br>
IR_Sensor.ino<br>
NANO_ESP32_Blink.ino<br>
Read_Switch.ino<br>
SerialToSerialB.ino<br>
Serial_To_Serial_BT.ino

<a href="/work/">Work Page</a>

<!--  ![](/assets/Electronics/)  -->
