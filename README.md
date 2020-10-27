# projet4_udacity_slam_rtab

# Real Time Appearance Based mapping - RTAB mapping

## *ROS Based* 

Use the below commnad to check the packages needed

$ `<rospack depends [name of package]>`


## Mapping use below command : which launches my_world in gazebo teleop node and rtab mapping 

$ `<roslaunch rtab_mapping main.launch>`

## localisation 

##### build the map using rtab 

#### copy the rtabmap.db file from .ros/rtabmap to package in workspace rtab_mapping/map

$ `<roslaunch rtab_mapping localisation.launch>`

##### To launch world file seprately:
$ `<roslaunch my_robot world.launch>`

##### To launch mapping file seprately :
$ `<roslaunch rtab_mapping mapping.launch>`




