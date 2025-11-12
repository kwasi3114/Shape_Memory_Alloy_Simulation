# Shape_Memory_Alloy_Simulation
Repository for Python and ROS/Gazebo simulation of shape memory alloys

How to use (sma_dynamic_model_v2_1.ipynb):
-this is a notebook file, you can open it in Google Colab
-if you run each cell, it should work and output a 10 second simulation
-the time can be changed, but the current array will have to be changed to reflect that
-for example, the sim is set to 10 seconds with a timestep of 0.1, meaning that an array of 100 current values is needed
-to create a gif you will have to modify the range in line 8 of the last section, so for 10 seconds the range is (1,101)
-for example, for a 5 second sim, it would be (1,51)
-feel free to reach out if any questions/issues come up 
