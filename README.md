# Implementación de sistema empotrado de control robot en plataforma de procesamiento de altas prestaciones
**Trabajo de Fin de Grado en Ingeniería Informática por la Universidad de Granada**

*Antonio José Blánquez Pérez*

---

Este trabajo pretende estudiar la viabilidad del uso de sistemas empotrados de altas prestaciones, como la familia Jetson de NVIDIA, en el control efectivo de robots colaborativos. Para ello se ha implementado un sistema de control para el robot colaborativo Baxter utilizando el middleware cROS, una implementación ligera en C de ROS más adecuada para sistemas empotrados. Además, se ha realizado un estudio en el que se compara el rendimiento y el consumo de una red neuronal por impulsos (SNN), basada en la estructura del cerebelo y utilizando el simulador neuronal EDLUT, en distintas plataformas.

Este proyecto obtiene conclusiones referentes a:
- El uso de cROS
- El uso de EDLUT en la plataforma NVIDIA Jetson
- La viabilidad del uso de SNN en plataformas de distintas características

Enlaces de interes:
- EDLUT: https://github.com/EduardoRosLab/edlut
- cROS: https://github.com/ros-industrial/cros
- EDLUT_ROS, el sistema de control en el que se basa el implementado en este proyecto: https://github.com/EduardoRosLab/EDLUT_BAXTER_DELAYS
- EDLUT_cROS: (El código será publicado cuando los nodos referentes a EDLUT estén implementados)
- EDLUT_Jetson_tools: (El código será publicado cuando los nodos referentes a EDLUT estén implementados)

---

This work aims to study the feasibility of using high-performance embedded systems, such as the NVIDIA Jetson family, in the effective control of collaborative robots. For this purpose, a control system for the collaborative robot Baxter has been implemented using the cROS middleware, a lightweight C implementation of ROS that is more suitable for embedded systems. In addition, a study comparing the performance and power consumption of a spiking neural network (SNN), based on the structure of the cerebellum and using the EDLUT neural simulator, has been carried out on different platforms.

This project draws conclusions concerning:
- The use of cROS
- The use of EDLUT on the NVIDIA Jetson platform.
- The feasibility of using SNN on different performance platforms.

Links of interest:
- EDLUT: https://github.com/EduardoRosLab/edlut
- cROS: https://github.com/ros-industrial/cros
- EDLUT_ROS, the control system on which the control system implemented in this project is based: https://github.com/EduardoRosLab/EDLUT_BAXTER_DELAYS
- EDLUT_cROS: (The code will be published when the EDLUT nodes are implemented)
- EDLUT_Jetson_tools: (The code will be published when the EDLUT nodes are implemented)
