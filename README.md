# A Review of Search-Based Path Planning Algorithms for Indoor Navigation of UV Sterilization Robots

Ultraviolet sterilization uses short wavelength ultraviolet-C (UVC), light for reduction of microorganisms
that may remain on the different surfaces after a standard process of cleaning. Advancing technology has
led to development of UV Sterilization Robots which can use this lights and clean highly contaminated
rooms while reducing human contact with the infected surfaces.

To increase the efficiency of these robots, we can study the existing path planning algorithms used in the
UV Sterilization Robots and review the existing comparative study of well-known path planning algorithms
to understand the advantages and disadvantages of the possible path planning techniques.


## Instructions for running the code:


* Unzip the submitted folder => "Output"
It's recommend that you save the folder on desktop and to run the program using the terminal in linux.


### For Dijkstra based path planning algorithm: 
Two .py files are required to run the Dijkstra Algorithm based program. 
  - frontend_dij.py 
  - backend_dij.py
  
Run the file named frontend_dij.py from dijkstra_trial to execute the code.

Once you run the program, you will see a OpenCV terminal showing output stepwise. 
You will have to press 'Q'/'Esc' key to start the next step after the execution of preious step

Python files needed:
---
frontend_dij.py
backend_dij.py

Result:
---
The blue region is the explored region. 
The green region is the unexplored region. 
The red region is the path from the start node to goal node.
The black region is the Obstacle space with clearance.

If there is a solution you can see the path in the pop up

Default Values:(X,Y)

Start Point = (10,10)
Given Contamination point 1: (475, 100)- 30%
Given Contamination point 2: (450, 680)- 50%
Given Contamination point 3: (200, 500)- 20%



## For A-Star based path planning algorithm: 

Two .py files are required to run the A-star Algorithm based program. 
  -frontend_astar.py 
  _ backend_astar.py 
  
Run the file named frontend_astar.py from astar_trial to execute the code.

Once you run the program, you will see a OpenCV terminal showing output stepwise. 
You will have to press 'Q'/'Esc' key to start the next step after the execution of preious step.


Py files needed:
---
frontend_astar.py
backend_astar.py


Result:
---
The blue region is the explored region. 
The black region is the unexplored region. 
The red region is the path from the start node to goal node.
The green region is the Obstacle space with clearance.

If there is a solution you can see the path in the pop up

Default Values:(X,Y, Orientation)

Start Point = (10,10,60)
Given Contamination point 1: (475, 100, 60)- 30%
Given Contamination point 2: (450, 690, 30)- 40%
Given Contamination point 3: (150, 500, 90)- 20%



## Built with
Python 3. 

## Libraries used
* numpy
* heapq
* math 
* OpenCV 

## Author
[Nupur Nimbekar](https://github.com/nimbekarnd)
