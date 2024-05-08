# Modelo URDF de un robot ejemplo 

Para lanzar en ros noetic este paquete se utilizan los siguientes comandos dentro del workspace:

	source devel/setup.bash
	roslaunch robot_model robot_xacro.launch

Esto lanzará el roscore con la simulación en gazebo y el diseño del robot. En otra terminal escribimos:

	rosrun teleop_twist_keyboard teleop_twist_keyboard.py

Y ya podremos controlar nuestro robot con el teclado.
