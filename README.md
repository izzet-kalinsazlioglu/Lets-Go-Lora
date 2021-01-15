# Lets-Go-Lora

This is a ready-to-go project example about Lora and Internet of Things.
we will make this project step by step.


## Steps 

1. Explain the project
2. Select component and modules and platform
3. Split the project
4. Run every modules with all features  
5. Combine the parts
 
## 1- Explain the project
River/Lake Healthy Monitoring System :
The system proposed is an advanced solution for smart river monitoring that uses IoT to make its real time data easily accessible over a very wide range. 
An efficient environmental monitoring system is required to monitor and assess the water conditions in case of exceeding the prescribed level of parameters (e.g., temp, CO and radiation levels) 
The system deals with monitoring river and climate changes like temperature, humidity, wind speed, moisture, light intensity, UV radiation and even water temp and quality; using multiple sensors. 
These sensors send the data to the web page and the sensor data is plotted as graphical statistics. The data uploaded to the web page can easily be accessible from anywhere in the world. The data gathered in these web pages can also be used for future references. 
The project even consists of an app that sends notifications as an effective alert system to warn people about sudden and drastic river water quality changes. 
For predicting more complex forecasts that can’t be done by sensors alone we use an API that analyses the data collected by the sensors and predicts an accurate outcome. 
This API can be used to access the data anywhere and at any time with relative ease and can also be used to store data for future use. Due to the compact design and fewer moving parts this design requires less maintenance. 
The components in this project don’t consume much power and can even be powered by solar panels. Compared to other devices that are available in the market the Smart River monitoring system is cheaper and cost effective.
This project can be of great use to environmental protection institutions, meteorological departments, weather stations and even the agricultural industry.

Key Words: Internet of Things (IoT), development boards, embedded systems, monitoring systems, ESP32, ESP8266, LORA, GPRS, Arduino IDE, PlatformIO and API.

![Architecture](/images/Lora Target System.jpg)




 ##  2-Select component and modules and platform

 ### Platform
mydevices.com (cayenne)
thingspeak.com
blynk.io
thinger.io
google spreadsheets or cloud
iot.telekom.com/de
cloud.telekom.de
thingsboard.io
bosch-iot-suite.com
Adafruit.io
iotguru.cloud
fogwing.io
ixon.cloud
...


 ### Base Station / Gateway :  Esp32 wifi bluetooth + SD card +  Sim7000 GSM GPRS  + GPS + Battery management + Solar input + Lora Extension    
 TTGO T-SIM7000G
 Lora Extension card RADIO TYPE SX1276
 Lora band 868.0 Mhz (Europe)

for more information:   
https://www.aliexpress.com/item/4000542688096.html?spm=a2g0o.cart.0.0.4f7c3c00Ojnqsh&mp=1
https://github.com/Xinyuan-LilyGO/LilyGO-T-SIM7000G



 ###  Station/Node 1 : Esp32 + LORA + GPS + Power Mng + Battery module 
 T-Beam V1.1 - NEO-M8N 
 Lora RADIO TYPE SX1262 
 Lora band 868.0 Mhz (Europe)

for more information:
https://www.aliexpress.com/item/4001287221970.html?spm=a2g0o.placeorder.0.0.12a6321eqmhrf2&mp=1 select 868 Mhz
https://github.com/Xinyuan-LilyGO/LilyGO-T-Beam


 ### Station/Node2 :  Esp32 + LORA +LCD + SD + (External Battery)
 TTGO LoRa32 V2.1 1.6

 for more information:
 https://www.aliexpress.com/item/4000419805182.html?spm=a2g0s.9042311.0.0.62174c4dVl79L3
 https://github.com/LilyGO/ESP32-Paxcounter?spm=a2g0o.detail.1000023.2.18e557d2y4e4E1



### Node Sensors
On completion of the project the following data will be available:
  External Temperature (DS18B20)
  Internal Temperature (BME280)
  Humidity (BME280)
  Barometric Pressure (BME280)
  Rain Gauge (Hydreon RG-ll)
  Wind Speed (Davis Anemometer)
  Wind Direction (Davis Anemometer)
  Water quality sensors ???


 ### Station/Node Box :
 for more information:  
 https://www.amazon.de/outdoor-motion-iPosible-waterproof-detector/dp/B07VJLDXRH/ref=sr_1_32_sspa?dchild=1&keywords=solar&qid=1598396732&sr=8-32-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEzVUI4SllOSTBRVFImZW5jcnlwdGVkSWQ9QTAwMjc1MTgzOTYxMVoyMDdZOVAzJmVuY3J5cHRlZEFkSWQ9QTAzOTgzNDIyWkwxTlA4TEVOSTRUJndpZGdldE5hbWU9c3BfbXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ== 



##  3-Split the project
We Split the project 3 part
  1- Send data Gateway to Cloud Platforms
  2- Send data Node to Cloud 
  3- Collect sensor data 



##  4-Run every modules with all features  

  1- Gateway/Base module examples







##  5-Combine the parts
 
 
 
