# glm-ps2

This is a port of the [glm](http://glm.g-truc.net/) library to the Playstation 2.

To use this, you should have your [ps2dev environment](https://github.com/ps2dev/ps2dev) setup to allow C++ code to 
compile. 

The Playstation 2's floating point format is not IEEE754 compliant. glm normally checks that the floating point format of the system is IEEE754 compliant, so these checks have been changed in this port. SIMD instructions are also different, so the simd types in glm don't work currently.
