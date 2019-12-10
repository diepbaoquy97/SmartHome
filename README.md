# Capstone Project
# Fall 2019

##SmartHome
----------
1. [Introduction](#introduction)
2. [Budget](#budget)
3. [Time Commitment](#time-committment)
4. [Mechanical Assembly](#mechanical-assembly)
5. [PCB/ Sodering](#pcb-soldering)
6. [Power up]
7. [Unit testing]
8. [Production Testing]


## Introduction

This is a tutorial which help you do the measuring temperature that using temperature sensor which names MCP9808. This hardware project is used to help the software project name SmartHome. The smarthome app will have some function such as temperature reading, door status, light control. Then the app will control these hardware. This help user overview and control their house easily.

To read the temperature from MCP9808 sensor, we use Raspberry pi 4 with a SD card contain Raspian and we use Linux to write a C program to read the temperature. First, we design the PCB board and do the solder to the socket into PCB. Then we just need to plug in the Raspberry and MCP9808 sensor to the PCB board.

I use the fritzing software to design the PCB board and send it to Humber prototype lab to make the PCB board. The fritzing file could be found [here](https://github.com/diepbaoquy97/SmartHome/blob/master/BaoQuyDiep-Latest.fzz)

## Budget
For me, my budget is approximate $100. The sensor was cheap. The most money I spend is Raspberry. Below is my budget
![budget](/Images/budget.png)

The parts that I got later is 

| Part      | Number |
| ----------- | ----------- |
| Micro HDMI   | 1        |
| USB to Ethernet cable   | 1        |
| Raspberry fan   | 1        |



I also got 2 x 8 pin socket from the prototype lab

## Time committment 
For this hardware project, it is easy to do and take about 9 hours to comple the project. We just need basic knowledge about circuit connection, soldering skill, Raspberry power up,etc. The longest time is that we have to wait for the parts we order and we also have to wait 2-3 business day for the prototype lab make our PCB board.

| Task      | Time |
| ----------- | ----------- |
| Ordering   | 90 minutes        |
| PCB design   | 120 minutes        |
| Soldering   | 60 minutes        |
| PCB power up   | 120 minutes        |
| Enclosure disign   | 90 minutes        |
| Enclosure pritting   | 45 minutes        |

In total, It takes approximately 9 hours to complete this project

## Mechanical Assembly
First, we need to connect the circuit from Raspberry to MCP9808 in order to read the temperature. There are 4 pin connection.
![Circuit](/Images/circuit.png)

The enclosure for raspberry is designed by the software names Coreldraw. The coreldraw design can be found 
[here](https://github.com/diepbaoquy97/SmartHome/blob/master/BaoCorel17comple.cdr)

The closure could be either printed in prototype lab or private outsite 3D printer.
The example images about enclosure could be found below:
![Enclosure1](/Images/Enclosure1.jpg)
![Enclosure3](/Images/Enclosure3.jpg)
![Enclosure4](/Images/Enclosure4.jpg)
![Enclosure5](/Images/Enclosure5.jpg)
![Enclosure6](/Images/Enclosure6.jpg)
For the case, just be careful when you put it into the case because it is easy to break

## PCB Sodering
The PBC board must be soldered in order to get connection. We use the socket and put it into the holes and solder it together. Then we just need to plug in the sensor into the socket
![PCB2](/Images/PCB2.jpg)

You could found a lot of tutorial about soldering online. Below is the video I found only, it is useful to help solder
[here](https://www.youtube.com/watch?v=aP_ebVWYzSk)

Below is the circuit that we need to solder
![Solder](/Images/BaoQuyDiep-Latest_pcb.png)
