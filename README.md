<h1> How to open and close doors </h1>
<p> 1. Navigate to the rcwest_half.wbt file and find the objects named "Door" </p>
<p> 2. For the door to be open, change the position parameter from 0 to 1 or 2 depending on how open one desires the door to be [0 being closed] </p>
<p> 3. Each door within the dorms are contained in the dorm's children objects, this is a good way to open a specific door as each door is not labeled </p>

<h1> How to run the simulation </h1>
<p> 1. Navigate to the f24_robotics_inside_simulation directory</p>
<p> 2. Perform a colcon build then source the install/setup.bash file </p>
<p> 3. From here enter "ros2 launch f24_robotics_inside_simulation launch.py" to run the simulation </p>

<h3> NOTE: The model is quite large, it is reconmended to lower the openGL graphics settings for better performance </h3>