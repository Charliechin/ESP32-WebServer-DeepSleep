# ESP32-WebServer-DeepSleep
ESP32 CAM web server that tries to connect to a known wifi, if not, the ESP32 will capture a picture and go to sleep for about 1 minute

## What is this all about?

Well, the idea is to put the ESP32 + a battery inside a plastic container and hide it in the street, so you can for example, take pictures in a given interval of time

## What does it do?

>1. ESP32 will try to connect to a wifi

I use my phone's hot spot. This way I can set up the camera and check its position/config etc...
Once I'm happy with how I planted the cam, I will got to the route [server_root]/reset and this will trigger a hard reset
Now I will deactivate the hotspot.

>2. If cannot find any known Wifi 


The ESP32 is going to take a picture with the flash ON and then go to sleep for a minute. Modify this parameter if you want to take less or more frequent pictures.

  
