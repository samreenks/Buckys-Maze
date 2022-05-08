# Bucky's Maze
A maze game coded in C that runs on [CPUlator](https://cpulator.01xz.net/?sys=arm-de1soc)
and uses the PS/2 keyboard and push buttons. 

The PS/2 Keyboard typed input uses the arrow keys to move the player across the VGA frame buffer. The push buttons are used to change the difficulty of the maze. Interrupts are used to keep track of deaths, difficulty modes and for pausing the game. Additionally, double buffering is used to display smooth animations on the VGA buffer. 


Bucky’s Maze was created for ECE243 (Computer Organization course at the University of Toronto). The source code cannot be shared due to the course outlines. A detailed description and screenshots of the game are displayed below. 

## Main Page

<img src="/images/menuscreen.png" width="600" />

## Demo

<img src="/images/demo.gif" width="600" />

## Difficulty Levels
Difficulty 1                          |  Difficulty 2                          |  Difficulty 3                           
:-------------------------------:|:---------------------------------:|:----------------------------------:
<img src="/images/difficulty 1.png" width="300" /> | <img src="/images/difficulty2.png" width="300" /> | <img src="/images/difficulty3.png" width="300" /> 
