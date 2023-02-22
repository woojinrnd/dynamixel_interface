# dynamixel_interface

##  Terminal command
>Terminal_1 :   roslaunch my_dynamixel_project dynamixel_interface_controller.launch   
  Terminal_2 :   rostopic echo -w 5 -c /joint_states 
  Terminal_3 :   rqt_topic  
  Terminal_4 :   rqt Plugin-topic-message publisher (joint_statss / desired_~~ )  

## Topic message Publisher setting  
>NUMBER_OF_DYNAMIXELS = 12
['joint_1', 'joint2','joint_3', 'joint4','joint_5', 'joint6','joint_7', 'joint8','joint_9', 'joint10','joint_11', 'joint12']  
[ 0.025, 0.025, 0.025, 0.025, 0.025, 0.025, 0.025, 0.025 , 0.025, 0.025, 0.025, 0.025 ]  
[ 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0 , 0.0, 0.0, 0.0, 0.0 ]  



>NUMBER_OF_DYNAMIXELS = 6  
['joint_1', 'joint2','joint_3', 'joint10','joint_11', 'joint12'']  
[ 0.025, 0.025, 0.025, 0.025, 0.025, 0.025]  
[ 0.0, 0.0, 0.0, 0.0, 0.0, 0.0]  

