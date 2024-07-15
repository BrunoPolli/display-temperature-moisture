# Project Temperature/Moisture 🌡💧

This is a project developed in NodeMCU ESP8266 v12-e and TFT display 240x240.

## Temperature display
The value is updated by requests in NodeMCU route '/update' by python scheduler:
https://github.com/BrunoPolli/temperature-moisture-scheduler

## Moisture value
A moisture sensor is responsible for reading analog values between 0-1023, that will be converted into a percentage format in code.  

## Icons
The icons and sprites for animation shown in display are created by me, using pixel editor PISKEL APP: 
https://www.piskelapp.com/.  

![termo](https://github.com/user-attachments/assets/d9b1ce5c-1015-4abe-a76f-69a0841270c6)
![waterDrop_80](https://github.com/user-attachments/assets/69108c88-63ed-4053-acf3-a16db195a230)

# Execution example

![IMG_8554](https://github.com/user-attachments/assets/f74c0919-df99-41fb-9bb8-711015608b6b)
