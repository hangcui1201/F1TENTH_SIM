### Starter Code of F1TENTH Simulator for [ECE484](https://publish.illinois.edu/safe-autonomy/)

#### University of Illinois at Urbana-Champaign

#### System: Ubuntu 20.04 + ROS Noetic (Gazebo 11)

#### F1TENTH Car

<a href="url"><img src="./images/track_porto.png" width="600"></a>  

#### Tunnel Environment

$ source devel/setup.bash  
$ roslaunch f1tenth-sim racecar.launch world_name:=racecar_tunnel  

<a href="url"><img src="./images/racecar_tunnel.png" width="600"></a>
<a href="url"><img src="./images/racecar_tunnel_camera.png" width="600"></a>

#### Walker Environment

$ source devel/setup.bash  
$ roslaunch f1tenth-sim racecar.launch world_name:=racecar_walker  

<a href="url"><img src="./images/racecar_walker.png" width="600"></a>

#### Levine Track Environment

$ source devel/setup.bash  
$ roslaunch f1tenth-sim racecar.launch world_name:=track_levine  

<a href="url"><img src="./images/track_levine.png" width="600"></a>

#### Porto Environment

$ source devel/setup.bash  
$ roslaunch f1tenth-sim racecar.launch world_name:=track_porto yaw:=0.75  

<a href="url"><img src="./images/track_porto.png" width="600"></a>

#### Barca Environment

$ source devel/setup.bash  
$ roslaunch f1tenth-sim racecar.launch world_name:=track_barca x:=-0.2 y:=-0.2 yaw:=-0.5  

<a href="url"><img src="./images/track_barca.png" width="600"></a>





