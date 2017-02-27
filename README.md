# Graphing-3D-Functions

This project utilizes the THREE.js library to create graphs of two-variable functions of the form f(x,y) and parametric functions of the 
form x(u,v), y(u,v), and z(u,v). The graphing is done by creating a function that returns a Vector3 for each value of the surface. This is
then passed through the THREE.ParametricGeometry function from which a mesh can be created representing the function passed in.

The dat.GUI interface is used to allow interactivity such as: updating the function due to user input, thanks to the expression parser
at silentmatt.com, and options for varying the bounds of the independent variables. 

Two versions of the files were created, one for Virtual-Reality compatability (only tested with the Oculus Rift DK2) and one for viewing
without a VR Head-Mounted Display. The code for allowing VR compatibility was created by *unknown*.
