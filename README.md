# some notes of the document of ai-car 

*the readme.md created on 2022.07.27*

## first edited

### background

<p>device:whalesbot MC601</p>

<p>software:wobot block studio version:1.2.3 or whalesbot all module MC601 version:2.4.4</p>

### special notes

the codes used will be uploaded after the competition,and the estimated time is the end of 2022.

*the above was edited on August 2, 2022*

## second edited

### some information about the whalesbot ai-car project

<p>project name: Intelligent warehousing of RoBoCom robots</p>

<p>competition theme:store up grain against dearth and Automated warehousing</p>

<p>environment:the environment of robot competition field is cold light source, low illumination and no magnetic field interference</p>

#### task modules:
  
##### task 1: Close the gate
  
  The robot considers it successful to close an electric switch to be opened and closed (the 126 degree beam is completely within the 50 degree beam)
  
##### task 2:Through access control
  
  The robot carries the work permit placed in the base to the access control, and it is deemed successful if the work permit completely enters the access control model box

##### task 3:Processing raw materials
  
  The robot considers it successful to put raw materials into the raw material processing area
  
##### task 4: Warehousing
  
  The warehouse area is above the site, and the shelf room is a temporary storage area for goods. The goods may be goods of different colors (red, orange, yellow, green, blue), or goods with pictures (milk drinks, electrical appliances, digital, fruits and vegetables). The goods are cubes with a side length of 5cm. Yellow and electrical digital goods will not be placed in the task box corresponding to the black guide line, and the specific quantity and placement position will be announced before debugging
  
  The robot puts red, orange and milk drinks on the left shelf, green, blue, fruits and vegetables on the right shelf (black board), and yellow and electrical digital on the middle shelf (red and black board). 10 points for each finished product placed on the shelves on both sides, and 20 points for each finished product placed on the middle shelf
  
##### task 5:Spot check
  
  At a product quality device on the field, there are four pictures with numbers pasted on it. The initial positions of the four pictures are randomly placed. The four numbers from low to high correspond to four temporary goods from left to right (specific pictures and corresponding positions are announced before the competition)

The robot moves the paddle to the left to start the selector. The selector number rotates until it naturally stops. The robot moves the number so that the number face is in front of the white beam below

50 points will be given if the robot recognizes this number and lights up the light corresponding to the image in front of the model (not returning to the base), and 20 points will be given if the robot arrives at the temporary stacking area to transport the corresponding goods back to the base

##### task 6:Mysterious Mission

There may be mysterious tasks in the competition. There is a task model. The task completion description and placement position will be announced by the referee on the scene

#### Additional information: robot configuration

1.Number and size of robots: 1 robot for each team; Before startup, the size is 30cm (length) × 30cm wide × 30cm (height); After starting, its structure can stretch by itself.

2.Controller: It is not allowed to change the controller in a single competition. Only one controller is allowed for each robot.

3.Actuator: The number of motors (including steering gear) used by each robot in each game shall not exceed 8.

4.Sensors: There is no limit to the types and quantities of sensors allowed for each robot.

5.Structure: except for the controller, actuator, sensor, wire, battery, wheel, gear and other parts of the robot, the robot is mainly a metal structure, and the number of other parts (plastic, cardboard, etc.) shall not exceed 30 and each part shall not exceed 10cm ³。

6.Power supply: The power supply voltage of the robot shall not be higher than 9V.
