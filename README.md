# mm-ma

Added AMCL Controller in mm_gazebo/controller folder.
  - Gripper and Arm
  - Mobile Base 
Added mm_gazebo/mm_world.launch
  - AMCL Controller node (Arm/Base)
Added mm_moveit_config
  - added sensor_3d.yaml in config
  - sensor_manage.launch
  - mm_planning_excution.launch
Added Teleop_twist package
  - can play around with it

Added Wood Model 
  - mm_gazebo/models/wood
  - rosrun mm_gazebo spawn_object.py
  
Single Robot almost okay with everything.

# Next 
  - multi_robot 
# Problem 
  - when launch two robot in gazebo in the rviz they can not find arm_base frame 
  - that is making no found location of robot 1, 2 
  - it means it can not play around with map(navigation)
  
