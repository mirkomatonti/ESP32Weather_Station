# ESP32 WeatherStation 
This project aims to build a weather station board for recording and uploading common weather data. The measured data can be uploaded to WUnderground or stored and displayed on a dashboard using a local Thingsboard server.

The custom PCB board is designed to work as a shield for the [ESP32 Dev board](https://www.az-delivery.de/it/products/esp32-developmentboard).

As an exercise, no external libraries are used to communicate with the sensors. All drivers are written from scratch. The framework used is ESP-IDF.

![Local installation, Salerno, Italy](https://i.ibb.co/0tcJq8N/photo-2021-09-26-17-05-20.jpg)

[Wunderground Page](https://www.wunderground.com/dashboard/pws/IBARON16/)

## Requirements
 - ESP32 Dev board 
 - Sparkfun Weather Meters
 - SHT31 Temperature/Humidty sensors
 - Custom PCB Weather Board
 - Wunderground API Key
 - ThingsBoard server local/cloud

## Getting started
- Set your WiFi credentials in "lib/Wifi/wifi.h"
- Signup on [Wunderground](https://www.wunderground.com/member/devices) and create a PWS.
- Configure a local installation of [Thingsboard](https://thingsboard.io/) or use their [Cloud](https://thingsboard.cloud/) service.
- Set WUnderground and Thingsboard API  in "lib/Cloud/cloud.h"

## Demo Dashboard
[Salerno, Italy](https://bit.ly/3zLmFFb)

[
![Salerno WeatherStation](https://i.ibb.co/GpYNhDy/Screenshot-2021-09-26-at-17-35-48.png "Salerno WeatherStation")](https://bit.ly/3zLmFFb)

## Hardware[EXPERIMENTAL]
![Custom PCB](https://i.ibb.co/HCTZjY3/Screenshot-2021-09-26-at-17-54-37.png)

## Update 16th April 2022
Unfortunately, after a heavy thunderstorm, the station stopped communicating. Once the box was opened, an orange liquid started flowing out, like the opening scene of the movie Titanic.


![Titanic](https://github.com/mirkomatonti/ESP32Weather_Station/blob/main/Titanic_Beginning_Scene.gif)
![Damage1](https://i.ibb.co/tm3cYzZ/photo-2022-04-16-11-28-03.jpg)

## License

This project is licensed under the MIT License.




