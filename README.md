# IIScInternWork
Work done during 2 months internship at IISc
Goal is to make a decentralised system for ground mapping and Autonomous navigation

## Materials Req.
  - Remote server
  - Mobile Robot Chassis
  - DC Motor
  - Motor Driver
  - TI's TIVA-C board(http://www.ti.com/tool/EK-TM4C123GXL)
  - Raspberry Pi-3b+
  - RaspiCamera
  ## Project Pipeline
  - Establish ROS node to publish raspicam data on the network(publisher).(DONE)
  - Establish ROS node on the server to read data(subscriber).(DONE)
  - Establish wireless connection between the two nodes.
  - On the server-side use the raspicam data to build map.
  - Use RRT on top of ORB-SLAM2 to develop map of the entire room.
  - Once the Map is developed use the Point cloud generated to find the open-area in the room for accurate path planning.
  - Use clustering algorithm to find the free space.

