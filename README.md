# MarchingSquares

Marching Squares is a 2D variation of the 3D Marching Cubes algorithm. 

Marching Cubes was used as a means of creating a 3D mesh by sampling from a scan of some real world object using a tensor of cubes. As the cube edges are clipped, its vertices are tested to see whether they are encompassed by the shape. If so, then those cubes are set to some predetermined state which will approximate the given shape. More information and links to more info can be found on the Wikipedia [Marching Cubes](https://en.wikipedia.org/wiki/Marching_cubes) page.

For my implementation in 2D, I used ancient OpenGL (GLUT was required for the project) and C++. All of my source is included in the single cpp file for ease of submission.
