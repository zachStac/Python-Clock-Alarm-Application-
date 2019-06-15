# Python-Clock-Alarm-Application-

Goal: The goal of this is to practice with variables that are constantly changing, and to add a GUI to it with some kind of user interface/ input. This application will also play with having a controller calling on several modules.

To Do:  
	Build a base clock with a GUI
	Try to add a radio button for 12 hour and 24 hour time, also add an ability to have both on the screen at the same time.
	Build out a module/s for an alarm/ timer function
	Practice passing user input form function and modules around to other modules and functions
	Add an ability to have a clock without the need for sys time being used
	
Project: 
•	I began by importing the sys, tkinter, and time modules. Then I defined a function that is the clock and will update and set the string for the GUI to present. Then I ended by adding a root main loop call. The clock works in a GUI there is currently no user interaction.  VERSION 1
•	I attempted to add a system that would let me add user input, but forgot how the root loop is called, I will need to build this component in a separate module and import it when needed. I will also need to look at re doing the loop for the clock and building it into a separate system and then pass the variable to the GUI better. Currently the clock works depending on the user input, but there is some kinks with the if statement, I will need to look at parsing instead maybe. VERSION 1.5


