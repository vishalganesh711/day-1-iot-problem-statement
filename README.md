## Day-1-
Day 1 ESP32 blink challenge, simulated in Wokwi. Blinks the built-in LED at one-second intervals.

## Wokwi simulation(https://wokwi.com/projects/476467542329593857)


## Day-2
Day 2 ESP32 project: toggle an external LED with a push-button using INPUT_PULLUP and software debouncing. Simulated in Wokwi.

## Wokwi simulation (https://wokwi.com/projects/476558929021495297)

# Day-3
Day 3 ESP32 project: read a potentiometer value on GPIO 34 and print it to the Serial Monitor every 500 ms. Simulated in Wokwi.

## Wokwi simulation(https://wokwi.com/projects/476560263759650817)

## Day-4
Day 4 ESP32 project: use a potentiometer to control an external LED’s brightness with PWM. Simulated in Wokwi.

## Wokwi simulation(https://wokwi.com/projects/476560443332563969)

## Day-5 ESP32 WiFi Connection
This project demonstrates how to connect an ESP32 DevKit v1 to the WiFi network provided by the Wokwi simulator. After successfully connecting, the ESP32 displays its assigned IP address in the Serial Monitor.

## Hardware Required:
ESP32 DevKit v1

No external components are required for this project.

## WiFi Configuration:
WiFi Network: Wokwi-GUEST
Password: No password required

## Steps to Run:
Open the Wokwi simulation.
Start the simulation by clicking Play.
Open the Serial Monitor.
Wait for the ESP32 to establish the WiFi connection.
Check the Serial Monitor for the IP address assigned to the ESP32.

## Wokwi simulation(https://wokwi.com/projects/476560812663182337)

## Day-6: Control LED Through Web Browser

This project demonstrates how to control the ESP32’s built-in LED using a simple web page. The ESP32 connects to the Wokwi virtual WiFi network and runs a web server that provides options to turn the LED ON or OFF.

## Hardware
ESP32 DevKit v1
Built-in LED connected to GPIO 2
No external components are required.
WiFi Configuration
Network: Wokwi-GUEST
Password: Leave blank
Wokwi Simulation

Run the simulation

## How to Use
Start the ESP32 simulation in Wokwi.
Open the Serial Monitor.
Wait until the ESP32 successfully connects to the WiFi network.
Copy the IP address displayed in the Serial Monitor.
Open the IP address in a web browser that can access the Wokwi simulation.
The web page will display options to control the LED.
Click LED ON to turn the built-in LED on.
Click LED OFF to turn the LED off.

## Web Server
The ESP32 runs a web server on port 80.

The following routes are used to control the LED:

/ledon → Turns the LED ON
/ledoff → Turns the LED OFF

This project shows how an ESP32 can be connected to WiFi and controlled remotely through a web browser.
## Wokwi simulation(https://wokwi.com/projects/476561376787807233)
