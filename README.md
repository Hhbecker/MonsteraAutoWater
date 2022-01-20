# MonsteraAutoWater

This repo contains the plans for an automatic plant watering system controlled by an arduino. The idea is to connect soil moisture sensors and a power controlled water valve to an arduino. When the soil moisture is low enough, the water valve will open for a set amount of time.

### Thoughts
* find arduino compatible soil mositure sensor and power controlled water valve
* take data on dirt mositure every 6 hours and send data to a text file on local computer to monitor success of system
* include an LED that lights up red when tank water is low
* set dryness thresholds specific to the type of plant (monstera vs fern)

### Arduino fast facts 
* good for controlling electronic components
* can control lights, motors, sensors, and wireless and bluetooth stuff
* good platform for building robots
* has a microcontroller not a microprocessor
* often powered by 9 volt batteries 
* arduinos come in all different shapes and sizes so you can get a bigger or smaller one depending on your project 
* they make “shields” which can connect to the arduino to give it bluetooth, cellular, ethernet, etc functionality 
* programmed using an Arduino language similar to C++

### Arduino Workflow
1. Write code on your own computer to program the arduino microcontroller telling it what to do
2. Connect the arduino to a computer to load the code onto the arduino
3. Disconnect the arduino from the computer and use the arduino as intended

