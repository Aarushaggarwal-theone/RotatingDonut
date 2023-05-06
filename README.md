# RotatingDonut

This program generates a spinning 3D donut using ASCII characters in the terminal. 

It uses trigonometry to perform the necessary calculations to create the 3D shape, and then maps each point in 3D space to a corresponding character in the ASCII "illumination" array based on its orientation relative to a light source. 

The resulting characters are then printed to the console to create the 3D donut illusion. This effct is created by the different densities of ASCII Characters that when placed together give off darker/lighter appearences which is used in mapping of ASCII art and images. 

## Run the c version

To run the C Version

once cloned the repository or copied the code

use ```$ make rotatingDonut.c``` to compile it and then ```$ ./rotatingDonut``` to run it
