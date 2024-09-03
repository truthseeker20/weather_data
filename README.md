# weather_data
Esp32 request weather data from openWeather API in every 10min, post it in a google sheet using webhook iffft, and aslo publish it on mqtt topics temp, hum, wind using adafruit.io mqtt broker, then go into deep sleep mode, wakes up after every 10 min. using timer, can also be woke up using a pushbutton, which gives instant reading.
