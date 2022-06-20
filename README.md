# Mini-Dog
The club's version of the Nova Spot Micro 3 by Chris Locke. Club project Started July 2021.

Add the path "~/Mini-Dog/ws\_mini\_dog/src/mini\_dog\_model/gazebo\_models" under the insert tab.

To modify the sdf cd into the "src/mini\_dog\_model" file. Make modifications to the .xacro file and run: 
"xacro ./urdf/mini\_dog\_model.xacro > ./urdf/mini\_dog\_model.urdf".
Then convert the urdf to an sdf using:
"gz sdf -p ./urdf/mini\_dog\_model.urdf > ./gazebo\_models/Mini\_Dog/mini\_dog\_model.sdf"

To view model in rviz run:
"ros2 launch mini\_dog\_model mini\_dog\_model.launch.py"
after setting up ros
