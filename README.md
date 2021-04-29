# Robotics_Final_Project Fetching Simulator
Downloading and Running Instructions:

Directory Structure:
Final_Project_Submission
IKPY
Controllers
Ball_Tracker
Ball_Tracker.py
TiagoSteel.urdf
Ball_Tracker2
Ball_Tracker2.py
TiagoSteel.urdf
Ball_Tracker3
Ball_Tracker3.py
TiagoSteel.urdf
Worlds
.IKPY.wbproj
IKPY.wbt
Robotics_Final_Project
controllers
P-Rob3_RY_Jonathan_controller
P-Rob3_RY_Jonathan_controller.c
P-Rob3_WB_Trevor_controller
P-Rob3_WB_Trevor_controller.c
TiagoSteelController
TiagoSteelController.py
TiagoSteel.urdf
Worlds
Final_project_world.wbt
.final_project_world.wbproj
Explanation of main folders:
IKPY: This directory has our 3 inverse kinematics attempts, along with a small world in which to test. The first controller being the original inverse kinematics. The second being the most accurate one. The third is an attempt to try a different way then what was found in documentations.
Robotics_Final_Project: This directory contains our overall project submission where we combined all of our robots and controllers into one world to show off their capabilities.

How to download and run the worlds:
Go to https://github.com/trgr5899/Robotics_Final_Project and download the Final_Project.zip
Unzip the folder
Open Webots
Go to file=>open world
Then choose IKPY.wbt to look at our work with inverse kinematics or Final_project_world.wbt to look at our main project submission
In order to run any of the controllers within the directories you must have IKPY installed, which can be done using “pip install ikpy”.
Lastly before running the simulation make sure to build the P-Rob3_WB_Trevor_controller.c and the P-Rob3_RY_Jonathan_controller.c. This can be done by clicking on the little gear at the top right of the webots text editor while having one of the C files open in the text editor window. Make sure to do it for both files 
Some other basic packages might need to be installed before running the simulation, but many of these can be installed by referencing google.
Now you are able to run our amazing simulations!
