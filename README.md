# Embedded-Systems
Emerging systems and technologies 

These projects were done on a CC3220 SimpleLink™ Wi-Fi® LaunchPad™ Development Kit Hardware setup. 

I will attach board data sheet and user manual for reference. 


Project 1

This project has all created materials and code listed as project.zip in attached files. This project used the launchpad TMP006 temperature sensor to read the room temperature (via I2C), an LED to indicate the output to the thermostat where LED on = heat on (via GPIO), two buttons to increase and decrease the set temperature (via GPIO interrupt), and the UART to simulate the data being sent to the server. Is simulated a thermostat type setup. In the project.zip there is two videos that show this in operation. 

This was my best project with this board as my code was 100% functional and output worked great. I thought my task scheduler setup with using if statements and modulus was a really simplistic design to implement with a timer. The most valuable things I learned from this project was using all three different types of interfaces such as UART, GPIO, and I2C. It helped me understand that communication better, and those are some things I may use or utilize in the future. I could have improved maybe on the organization of my global variables and methods in my code.I included comments to make this project readable, and easy to understand, and I always like to use easy to look at white space, which helped code look clean and organized.  


Controlling an LED via serial

Another project consisted of Controlling an LED from the serial port using a state machine.This code used a switch case statement via UART, and looped thorugh reading character by character waiting for the user to type "ON" on the keyboard. When on was typed the LED came on via a GPIO command, and when off typed the LED turned off via a GPIO command. The code for this will be attached in a folder named LED project. 

This project wasn't 100% functional and it could be improved. My switch case statement was a good idea for the state machine I think but I don't think it was a 1 byte state like I tried to make it. I shouldn't have needed variables for first character, second, etc. The characters needed to follow a set sequence.  It was cool to implement a state machine with a switch case statement, which was probably the most valuable thing I learned on this project. The resource explorer and code composer studio were great resources in helping understanding the background TI code. I included comments to make this project readable, and easy to understand. I used easy to look at white space, which helpef code look clean and organized.  

