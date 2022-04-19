# CS-350
Embedded Systems

*Summarize the project and what problem it was solving.*

This project created a simple thermostat using the CC3220S Microcontroller. A target
temperature can be set on the board, which is compared from the reading from the temperature
sensor. Timers are used to check flags that are raised when a button is used to change the target
temperature. Another timer is used to compare the actual temperature to the target temperature.
If the target temperature is lower than the set temperature, the red LED is turned on which simulates
the heater being turned on.

What did you do particularly well?

In this project, I had trouble copying the starter code that I was provided with. The formatting would not
copy correctly, so I had to go through the code line by line to ensure that I had an accurate version of the template.
In this process I was able to keep the code organized, with proper indentation and formatting. It makes the code
easier to read, and so that anyone unfamiliar to the code is able to approach it and understand the logic.

Where could you improve?

I had trouble diagramming the task scheduler for this project because it is not built as a standard state machine. 
I did my best to diagram and explain how the timers work with the draw.io diagram that is included with the project.

What tools and/or resources are you adding to your support network?

In line comments support the code, as well as a diagram explaining the task scheduler. 

What skills from this project will be particularly transferable to other projects and/or course work?

This project gave me the condifence to work with embedded systems, using timers and interupts to create code 
that is much different than what I've programmed for desktop systems previously. This course opened my mind to 
how to program these systems, and also brought to light how prevelent these systems are in my daily life. So many
things that I take for granted are made possible because of embedded systems!

How did you make this project maintainable, readable, and adaptable?

A careful eye for formatting, proper commenting, best practices, etc. The code is meant to be organized
so that anyone unfamiliar with it can quickly understand it's functionings. 
