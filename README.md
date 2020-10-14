# LED Project

Started the raspberry pi LED project. Firstly, we unboxed the raspberry pi and screwed the fan into the case to stop it from overheating. We then fitted the raspberry pi into the case and connected it to a monitor, keyboard and mouse. After this we made sure the Raspbian software was downloaded on the raspberry pi. It was already installed so we proceeded to update the software and try commands in the terminal.

Next day: Today we used many of the hardware components in the starter kit that came with the computer. We used an LED, a breadboard, a 220H resistor and two wire connections. We used these to create the circuit that allows the LED to light up. After finishing the circuit, we had to do a lot of research and run many commands to figure out how to download idle from python3. After a lot of research and failed attempts we managed to download idlex instead which worked fine. We then typed our code into idlex and ran it in the command terminal. Firstly, it worked but soon after it would no longer flash and we had to redo the circuit. This worked fine and we made the LED flash three times in a row and then turn sleep. AFter this we tweaked the code to make the duration of the flashes different.



![image1](./images/raspberrypi-1.jpeg)


![image1](./images/raspberrypi-2.jpeg)

Today we accessed Microsoft Azure.
We created an Iot hub.
Used a raspberry pi simulator.
Added device to Iot hub.
Managed simulator from Iot hub by turning LED on and off.
Created a new Iot hub for the physical device.
Added real raspberry pi device.
Installed Putty on laptop.
Remotely connected over the internet to raspberry pi device using Putty and SSH.
Had to obtain the IP address using shell command `ifconfig`.
IP address was 192.168.0.207.
We downloaded and installed Visual Studio Code to allow us to authenticate to Github to clone the repo [https://github.com/Azure-Samples/azure-iot-samples-node.git](https://github.com/Azure-Samples/azure-iot-samples-node.git).
We then installed the sample packages from the repo using the command `npm install`.


![image1](./images/raspberrypi-3.jpeg)
