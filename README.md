# Proyecto de ROS con Turtle Sim
Este proyecto utiliza ROS (Robot Operating System) y Turtle Sim para controlar el movimiento de una tortuga simulada. El objetivo es demostrar el uso básico de ROS y cómo interactuar con el entorno de simulación de Turtle Sim.

# Ejecución del proyecto
Para ejecutar el proyecto hay que:
1. Ejecutar ```roscore``` en una terminal de ROS
2, Ejecutar ```rosrun turtlesim turtlesim_node``` en otra terminal de ROS
3. Ejecutar devel\setup.bat, seguido de rosrun turtle_unida src/mover.py.
   Obs: las mismas deben ser ejecutadas en otra terminal de ROS, una seguida de otra. Para ejecutar el devel se debe estar en la carpeta donde esta el devel. Es decir, por ejemplo cd .., cd .. c:\ Milagro_Martino > devel\setup.bat
   4. Ahora puedes observar cómo la tortuga simulada se mueve de acuerdo con los comandos enviados por el nodo mover.py.
