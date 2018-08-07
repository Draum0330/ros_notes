# ROS笔记-by Draum
## Day1
### turtlesim-小乌龟基础键盘控制
roscore
rosrun turtlesim turtlesim_node
rosrun turtlesim turtle_teleop_key 
### ROS基础框架
             ——————————————
            |  ROS Master  |
             ——————————————
                   ||
                   \/
      ____________________________
     ||                          ||
     \/                          \/
 ____________     message   ____________
|  发布者    |————————————>|   订阅者    |
 ————————————               ————————————
     ||                          ||
     \/        ____________      \/
      ———————>|  topic     |<—————
               ————————————

