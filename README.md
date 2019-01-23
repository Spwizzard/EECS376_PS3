# my_stdr_control
An minimal, example node to illustrate control of the STDR mobile robot with open-loop commands. From the starting point, the robot will travel to the upper-left corner of the maze.

## Example usage
`roslaunch stdr_launchers server_with_map_and_gui_plus_robot.launch`
to start the simulator.  Run a simple, open-loop command sequence with:
`rosrun my_stdr_control stdr_open_loop_commander'

    
