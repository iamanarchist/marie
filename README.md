marie
=====

Beautiful and Smart Operating System - Inspired by Her

Summary
-----

Marie is a Linux distro based on ArchLinux. 

Design Goals
-----

- combine social network and human-like operating system together
- understand the user intention and provide suggestion and assistance
- use gesture (leap motion) as well as touch, voice, camera (kinect), and keyboard input
	- for example you can shake your head to say "no"
	- just like what **Tony Stark** has with **JARVIS**
- the system is not just operating "the machine" but "each moment of your life"
- the user interface should be super intuitive and beautiful
- designed with distrbuted computing in mind - powered by GPU server clusters
- userland is written in Go and C++ with minimal dependencies
- use latest kernel to provide hardware compatibility
- self-enhancing, no more manual software upgrade to minimize user intervention
- seperate developer mode and user mode
- provide a foundation for userland tools
	- process and resource are shared and distributed across the cluster
	- snapshot function should be provided to serialize/deserialize states
- built-in support for 10G/40G infiniband by default
- built-in support for VM/dockr so we can create raw Linux machine with simple commands
- restricted hardware requirement, we don't support low-end hardware
	- two or more monitors, SSD, GPUs, LeapMotion, Kinect are required
	- need a AWS (or alike) account for backup configuration and states
- last but not least, **change the world**
