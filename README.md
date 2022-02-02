# LCD1602
## Introduction
In this getting started with LCD module tutorial, we are going to learn interfacing an LCD module with  Arduino  Uno.

![LCD1602][lcd]

### Hardware Used
16x2 LCD module
Arduino UNO

### Software Used
Arduino IDE

### Libraries Used
LiquidCrystal Library - Will available in Arduino IDE by default - For the first method.

### A Little Bit About LCD Modules...
LCD modules are coming in different colors and sizes with a different number of displayable characters. the most commonly used one is LCD1602 which can display 16 characters in each line, that is a total of 32 characters. Some other sizes are,

LCD1604 - 16 char / 4 line
LCD2004 - 20 char / 4 line
LCD1602 - 16 char / 2 line
LCD1601 - 16 char / 1 line etc...

### PIN Description
![description][des]

### Circuit
![Circuit1][circuit1]

![Circuit2][circuit2]

First connect the ground of Arduino to the VSS of the LCD.
Then connect the V0 of the LCD to the ground for full contrast
Then connect RW to the ground for selecting write mode
Then connect K, which is the ground of backlight LED also to the ground.
Then connect the 5V of Arduino to the VDD of the LCD module.
Then connect the digital pin 12 of Arduino to the RS of LCD module.
Then connect the digital pin 11 of Arduino to the E of LCD module.
Then connect the digital pin 5 of Arduino to the D4 of LCD module.
Then connect the digital pin 4 of Arduino to the D5 of LCD module.
Then connect the digital pin 3 of Arduino to the D6 of LCD module.
Then connect the digital pin 2 of Arduino to the D7 of LCD module.
And finally connect the 3.3V of Arduino to the A of LCD which is the anode of backlight LED.


**Also the data sheet is in Docs**














[lcd]:https://hackster.imgix.net/uploads/attachments/924857/img_0510_auRlYlz8t3.JPG?auto=compress%2Cformat&w=680&h=510&fit=max
[des]:https://hackster.imgix.net/uploads/attachments/924840/screen_shot_2019-06-13_at_1_17_47_pm_XX6RqU7T6j.png?auto=compress%2Cformat&w=680&h=510&fit=max
[circuit1]:https://hackster.imgix.net/uploads/attachments/924841/lcd.jpg?auto=compress%2Cformat&w=680&h=510&fit=max
[circuit2]:https://hackster.imgix.net/uploads/attachments/924842/screen_shot_2019-06-13_at_1_18_55_pm_DhHtccXH09.png?auto=compress%2Cformat&w=680&h=510&fit=max
