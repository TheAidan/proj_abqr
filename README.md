# proj_abqr
This is the project page for my Senior Thesis. 

Most of the codebase consists of functions allowing relatively complicated actions to be abstracted to a level that is equal to the simplicity of the action that will be performed, such as turning 15 degrees from the current heading, or etc.

Simple was the mantra during much of the design process, and the code does an acceptable job at representing that. 

Weaker links include the grid system. I am attempting to abstract it to what is functionally a Cartesian plane where every point above a certain resolution contains an additional state value. 

Here is a brief summary of each file and its functionality

1. angledet.py: calculates the angle between the current position and heading and a point of destination. Used for trajectory
2. detnewxy.py: calculates a destination point using the angle and distance from the current location
3. gaussfunction.py: calculates concentric circles spaced in a Gaussian manner around a point, creates a rough field of likelihood
4. planeconversion.py: calculates the location on the Cartesian plane of points in the distance
5. planeconversionvisualization.py: graphical representative of scanned points on the cartesian plane
