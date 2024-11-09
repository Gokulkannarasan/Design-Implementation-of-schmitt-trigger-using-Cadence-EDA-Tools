# Design-Implementation-of-schmitt-trigger-using-Cadence-EDA-Tools

Aim:
The aim of this assignment is to analyze the working principles of the Schmitt Trigger, a bistable multivibrator circuit that converts an analog input signal to a digital output. This study examines the unique hysteresis characteristic of the Schmitt Trigger, which prevents noise-induced fluctuations in the output signal by introducing separate threshold levels for switching between high and low states.
Tools Required:
•	Personal Computer
•	Cadence Virtuoso Software

S C H E M A T I C S I M U L A T I O N
PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION
Commands to get into Cadence
1.	Right Click and open the terminal window
2.	Type the following commands as follows and press enter.
•	csh
•	source /cadence/install/cshrc
•	virtuoso 
Procedure for Schematic simulation using Cadence

1.	Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”
2.	Close the 2nd window
3.	Use 1st window i.e virtuoso window(CIW) for further processing.
i.	Create a New Library
ii.	Create Schematic Cell view.
iii.	Create the Symbol for schematic Cell view.
iv.	Create the test Cell view.
v.	Analog simulation by spectre


i)	Procedure for Creating New Library.
•	File –New – Library
•	Name : Give name for ur library Ex: VLSILAB_EXP_1
•	Enable Attach to an existing technology library, Click OK
•	Attach the library to the technology library gpdk045.Click OK
ii)	Create Schematic Cell view.
•	Go to 1st window i.e virtuoso(CIW)
•	File-New-Cell view
•	Setup the new file form
	  Library: Select the one you a created.
	  Cell : Give the experiment name Ex: Inverter View_Schematic
	  Type: Schematic press OK
•	Add the required components from the libraries and make the connections.
	Go to instance fixed menu or use shortcut key “I” from keypad to go instances
	Click on browse. This opens the library browser
	Now select the appropriate library for components like 
	Gpdk45 ------------------------nmos1v,  pmos1v
	Create Input and Output pins
	Make the connections by using fixed narrow wire key
	Click Check and Save button
![Screenshot (118)](https://github.com/user-attachments/assets/d73dc76b-f425-4a33-8d58-65987a57e403)




For Transient Analysis Settings and Output
![Screenshot (121)](https://github.com/user-attachments/assets/4daf906a-4705-4df9-89c6-766ac9cce935)



![Screenshot (120)](https://github.com/user-attachments/assets/08839372-4016-40f0-a352-37ecd1ea2c4e)





 

Results:
1.	The experiment successfully demonstrated the design and implementation of a schmitt trigger using Cadence EDA tools. 
2.	The successful verification through schematic, layout, and simulation underscores the effectiveness of using Cadence EDA tools for digital circuit design.
