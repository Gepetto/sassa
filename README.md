# Sassa Quadruped Robot

"Sassa" is an ongoing open-source, open-hardware quadruped robot project, currently in development at LAAS.

**Image of the Robot**

*[To do: Insert an image of the robot]*

"Sassa" is named after a small antelope found in eastern and southern Africa, known in English as the "Klipspringer." You can learn more about the animal [here](https://en.wikipedia.org/wiki/Klipspringer).

This robot is entirely open-source (including hardware), making it a unique and dynamic project. However, as the project is still in progress, it might not be easy to replicate.

The primary motivation behind this platform is to experiment with and conduct research on mechanics, electronics, and software. As the platform continues to evolve, efforts will be made to simplify the reproduction process.

"Sassa" has a design architecture similar to the "MIT Mini Cheetah." It utilizes 12 actuators from Myactuator, specifically the [RMD-X8](https://www.myactuator.com/product-page/rmd-x8). The control electronics of these actuators have been replaced by our custom opensource motor driver, which can be found [here](https://github.com/open-dynamic-robot-initiative/open-motor-driver-initiative).

The robot's central computer, for now, is a Raspberry Pi 4. We use our master board to centralize communication between the computer, motor driver, and IMU. More information about the master board can be found [here](https://github.com/open-dynamic-robot-initiative/master-board).

The robot's parts have been FDM 3D printed on an Ultimaker S5, using Ultimaker Tough PLA and Ultimaker Breakaway support material.
