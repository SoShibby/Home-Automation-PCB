# Home-Automation-PCB
This is a Home Automation PCB for the Raspberry Pi. The board contains the following features:
- Switching two pair of speakers on and off independently.
- RF transmitter for controlling devices such as [Nexa](http://www.nexa.se/LGDR3500.htm) switches.
- 4 buttons.
- IR Receiver used for receiving commands from remote controls.
- 2 Humidity and Temperature sensors.
- 3 IR LEDS/Blasters for controlling TV, Radio, Decoders etc.

If you want to modify the PCB and add/remove components then I recommend that you use [Fritzing](http://fritzing.org) 
(you only need to open the following file [Home Automation PCB](https://github.com/SoShibby/Home-Automation-PCB/blob/master/fritzing/Home-Automation-PCB.fzz) in the Fritzing application and you are good to go).
If you want to order this PCB I recommend that you use [OSH Park](https://oshpark.com), you can find this project [here](https://oshpark.com/shared_projects/Q0L6N2mS)
and if you click the order button, you will receive an exact copy of the Home Automation PCB (note that you will only get
the PCB and not the components that are listed [below](https://github.com/SoShibby/Home-Automation-PCB#bill-of-materials)).

GPIO Pins
---------
| GPIO Number | Component         | Direction |
| :---------- | :---------------  | --------: |
| 5           | Speaker 2         | Output    |
| 6           | Speaker 1         | Output    |
| 9           | RF Transmitter    | Output    |
| 12          | Button 1          | Input     |
| 13          | TV Elevator Up    | Output    |
| 16          | Button 2          | Input     |
| 19          | TV Elevator Down  | Output    |
| 20          | Button 3          | Input     |
| 21          | Button 4          | Input     |
| 23          | IR Receiver       | Input     |
| 24          | Humidity Sensor 2 | Input     |
| 25          | Humidity Sensor 1 | Input     |
| 26          | IR LED/Blaster    | Output    |

PCB Top View 
------------
![PCB Top View](https://github.com/SoShibby/Home-Automation-PCB/blob/master/images/PCB-Top-View.png)

PCB Bottom View 
---------------
![PCB Bottom View](https://github.com/SoShibby/Home-Automation-PCB/blob/master/images/PCB-Bottom-View.png)

Bill of Materials
-----------------
| Amount | Part Type                         |
| :----- | :-------------------------------- |
| 4      | 1N4004 DO-41 400V 1A              |
| 15     | Break away female headers - 2 Pin |
| 2      | Break away female headers - 3 Pin |
| 2      | Break away female headers - 4 Pin |
| 1      | Break away female headers - 6 Pin |
| 1      | 8.2Ω Resistor                     |
| 4      | 1kΩ Resistor                      |
| 5      | 1.2kΩ Resistor                    |
| 2      | 4.7kΩ Resistor                    |
| 4      | 10kΩ Resistor                     |
| 1      | IDC Male PCB 40-pol 2.54mm        |
| 2      | G5V-1-DC5 Relay                   |
| 1      | SMI-05VDC-SL-2C Relay             |
| 2      | VR05R051'A Relay                  |
| 1      | ULN2803 Darlington Array          |
| 1      | TX433N                            |