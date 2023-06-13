# Soccer-Ball-Tracker
A neuron bot that tracks the soccer ball and detects it  and then adjusts its control operations to move towards the ball to kick it.

* Create a catkin workspace and a ros node using the commands
  ```mkdir –p myWorkspace/src```
```cd src```
```ros2 pkg create --build-type ament_python myPackage --dependencies rclpy std_msgs --node-name myNode```
* After node creation place these files in the node for running
* Launch the node using the command
```ros2 run myPackage ball_tracker.py```

* You can place any robot in any environment you like through adjusting the hsv values of the ball and the robot would move accordingly

