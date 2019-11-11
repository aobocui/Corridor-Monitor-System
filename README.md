# Corridor-Monitor-System
It is based on STM32 micro controller
Remote control is used for divergent functions, the communication is accomplished by bluetooth:
Button 1 is pressed: show the distance got by ultrasonic ranging module. Once the distance is less than 5 m. The buzzer would work for giving an alarm
Button 2 is pressed: show whether there is a person which is detected by HC-SR501Infrared pyroelectric sensor.
Button 3 is pressed: show the temperature. Once the temperature is less than 32, it shows 'warm' on the screen. Once the temperature is lager than 32, it shows 'hot' on the screen.
Button 4 is pressed: show the humidity. Once it is less than 1000, 'dry' is showed on the screen. Once it is larger than 1000, ' moist' is showed on the screen
Button 5 is pressed: show whether there are someone touch the touch switch sensor on the screen.
