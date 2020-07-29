# Line-Following-Drone

1. To see the simulation of drone movements in Gazebo: \
       <t> run the following command in a terminal: \
                roslaunch px4 mavros_posix_sitl.launch \
        in another terminal run: \
                python line_follower.py 
                
    Make sure you have the installations of gazebo, mavros, and other installations done before running the above terminal commands 
    
    
2. The "line_edge_detection.py" waits for the user to press a key other than 'q' to move to next frame. This helps to visualize each frame properly. To close the script press 'q'. On pressing 'q', an image "Defective Frame.jpg" will be created automatically. So whenever you find that the line does not get detected properly in a frame, you can press 'q', and run the "defective.py" script to find the suitable parameters for that frame. 

