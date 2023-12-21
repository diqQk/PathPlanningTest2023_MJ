# Path Planning Algorithm Test
This is Path Planning Algorithm Test on ROS2-PX4 Environment.


## Node Construction
### Publisher Node
This node pubilshes a message with Image Data Path.

### Subscriber Node
This node subscribes a message with Image Data Path.
And it runs a path planning algorithms and calculates a cost in terminal.

## Run 
Navigate a ros2 workspace

### Terminal 1 
colcon build --packages-select py_pubsub

### Terminal 2
source install/setup.bash
ros2 run py_pubsub talker

### Terminal 3
source install/setup.bash
ros2 run py_pubsub listener


