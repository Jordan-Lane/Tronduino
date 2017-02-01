# Tronduino

Tronduino was a group project by Jordan Lane, Mark Griffith, and Brad Ofrim for our Undergraduate C++ course. 

For our end of the year project our group decided to design, code, and debug a TRON game for the Arudino Mega. This project was a lot of fun to work on, and it introduced us to the pros and cons of embedded systems. 

## Hardware 

* Arduino Mega Board
* USB Arudiuno Connection
* Adafruit TFT LCD Screen (160 x 128)
* 2 Joysticks
* Potentiometer 
* Wires

## Setup Instructions
* 5V -----> Bread Board Positive Bus
* GND ----> Bread Board GND BUS

LCD Screen
* GND ----> Bread Board GND Bus
* VCC ----> Bread Board Positive Bus
* RESET -----> Digital Pin 8
* D/C -----> Digital Pin 7
* CARD_CS -----> Digital Pin 5
* TFT_CS -----> Digital Pin 6
* MOSI -----> Digital Pin 51
* SCK -----> Digital Pin 52
* MISO -----> Digital Pin 50
* LITE ----> Bread Board Positive Bus

Joystick (P1)
* VCC -----> Bread Board Positive Bus
* VERT -----> Analog Pin 0
* HORZ -----> Analog Pin 1
* SEL ----> Digital Pin 10
* GND ----> Bread Board GND Bus

Jostick (P2)
* VCC -----> Bread Board Positive Bus
* VERT -----> Analog Pin 2
* HORZ -----> Analog Pin 3
* SEL ----> Digital Pin 11
* GND ----> Bread Board GND Bus

## Uploading Instructions
* Put tron.cpp and makefile in same directory
* Connect Arduino to Computer and select correct Arduino port
* Compile code by entering 'make' into terminal
* Upload code to board by entering 'make upload' into terminal
* Have Fun!

## Bonus
On the Start Menu hold down the Joystick button for approximately 5 seconds. This will put the player in one player mode against our bot!

The main menu allows the user add obstacles to the course and change the colour and speed of the TRON bikes. 

