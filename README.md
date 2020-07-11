# listen_to_topic_and_save
Repository, that listenes to topic and saves as images to disk in .exr

# Requirements
ROS, for example melodic
opencv 3.3.1 or opencv 3.4.3

# Installation
1. Create folder "catkin_ws/src" somewhere
2. Go the new created folder, into src folder
3. git clone https://github.com/IaroslavS/listen_to_topic_and_save.git
4. cd ..
5. catkin_make
6. source devel/setup.bash
7. rosrun listen_and_save listen_and_save -t "name of topic" -p "path for saving images" -e "encoding"

By default: 

    -t: /stereo/depth
    
    -p: ""
    
    -e: 32FC1

for path don't put symbol '/' after the last folder, or there'll be error
