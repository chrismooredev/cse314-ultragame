# CSE 314 - Ultragame

# Summary of the project
The project will be a continuous guessing game, where one can score points according to how fast they can estimate a target height within a given timeframe. The game will use a distance sensor for measuring height, and use a piezo buzzer to provide the player feedback throughout the guessing period. It can then display the score on a small screen, and tweet it.

# Project objectives/features
The application is a playable game that allows users to test their dexterity and induction skills. The core of the game will be controlled through an ultrasonic distance sensor, pointed upwards, that a player places their hand over to control an input height. The input height is compared against a random value over a set guessing period, and the player continuously receives feedback through the piezo buzzer (represented by pitch) and an OLED screen (represented by screen density, where all black is nowhere close, and all white is on target). This process repeats for a few iterations, until finally a numerical score is displayed on the OLED screen, and submitted to Twitter. The game starts with a player's hand over the sensor for a few seconds.

# Textbook recipes involved in the project (recipe # and title)
1. 13.18 - Measuring Distance Using Ultrasound
2. 15.6 - Making a Buzzing Sound
3. 14.5 - Using an OLED Graphical Display
4. 16.5 - Sending Tweets Using ThingSpeak

# List of hardware components
1. HC-SR04 Distance Sensor
  - 470 & 270 Ohm resistors
2. Piezo
3. OLED Display

# List of software components
1. Python Library - Adagruid SSD1306
2. Python Library - Pillow

# List of additional services
1. ThingSpeak
2. Twitter
