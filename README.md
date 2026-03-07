# DIY CNC Pen plotter V1

## Description
A CNC pen plotter made using Arduino UNO, GRBL, 23BYJ-48 stepper motors. 
Inspired by designs by Chronic Mechatronic https://youtube.com/@chronicmechatronic?si=Jg6vBjnirjZI561L

## Hardware
- Arduino UNO
- 23BYJ-48 stepper motors
- ULN2003 stepper mototr drivers
- Tybe B printer cable (2m)
- Jumper wires
- Pulleys
- Thread (the most unstretchable kind you can find)
- SG90 servo motor
- Limit switches
- Telescopic drwer hinges
- Plywood base

## Firmware
- MIGRBL (fork of GRBL that allows control of servo motor through the spindle/laser control)

## Software
- Universal Gcode Sender (latest version)
- Inkscape

## Images
- <img width="2245" height="1587" alt="image" src="https://github.com/user-attachments/assets/b520a1e7-69e0-4993-b296-c85157992f7e" />
- <img width="947" height="945" alt="image" src="https://github.com/user-attachments/assets/cb80efb1-eaee-4a62-9d78-a77e84eb2e39" />
- <img width="701" height="780" alt="image" src="https://github.com/user-attachments/assets/8e310215-b6d2-4fe2-80a3-359a5344de84" />
- <img width="703" height="933" alt="image" src="https://github.com/user-attachments/assets/fecc4f9f-d9f0-46db-a23a-8878adaf9b18" />
- <img width="701" height="708" alt="image" src="https://github.com/user-attachments/assets/748f83cf-24d5-4e19-8529-d10f3cadb5d4" />
- <img width="1675" height="941" alt="image" src="https://github.com/user-attachments/assets/516cb571-46ae-422c-ad5a-a31334119746" />

## Results
- Accuracy within 1.5 millimeters
- Speed of upto 4 mm/s
- The threads can slip on the pulleys. This leads to drift overtime
- Several probelms with the inkscape extensions which very fixed with brute forcing the process
- The machine is too slow to draw anything more than outlines. Anything more takes hours to finish
- Since the machine is made of plywood and MDF, and held together with hot glue and screws, if the threads get stuck somewehre, the machine tends to implode as the mototrs keep pulling everything inwards



