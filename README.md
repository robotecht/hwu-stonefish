# Stonefish Tutorial

Stonefish is a C++ library combining a physics engine and a lightweight rendering pipeline. The physics engine is based on the core functionality of the Bullet Physics library, extended to deliver realistic simulation of marine robots. It is directed towards researchers in the field of marine robotics but can as well be used as a general-purpose robot simulator. 

Website: https://stonefish.readthedocs.io/en/latest/index.html 

The Stonefish library is used to build a dynamic simulation world with rigid body physics, geometry-based hydrodynamics and impulse-based collisions. Apart from the pure physics simulation, the Stonefish library delivers a wide spectrum of virtual actuators, sensors and communication devices, including IMU, odometry sensors, GPS, compass, pressure sensor, Doppler velocity log (DVL), profiler, multi-beam sonar, communication acoustic modem and the ultra-short base line (USBL) device. 

Another unique feature of the Stonefish library is its custom rendering pipeline, closely coupled with the physics engine. Special focus was put on the simulation of the underwater environment, where effects of wavelength-dependent light absorption and scattering based on Jerlov measurements were considered. 

![image](https://github.com/robotecht/hwu-stonefish/assets/170650493/09901ae1-d80b-4085-a0aa-22610d915c46)

## Installation 
### System Requirements: 
**Processor:** Multi-core processor 

**Minimum Graphics Card:** Nvidia GeForce 400 series, AMD Radeon HD 5000 series 

**Operating System:** Linux Ubuntu 

The minimum requirement is the support for OpenGL 4.3. If the GPU is not fulfilling the requirements, it is still possible to run simulation in console mode, with limited functionality. 

## Dependencies 

The following dependencies have to be installed prior to building the library: 

[OpenGL Mathematics ](https://github.com/g-truc/glm) libglm-dev, version >= 0.9.9.0

[SDL2](https://github.com/g-truc/glm) libsdl2-dev



