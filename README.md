# Landmark transformation and ICP

This software written in C++ with VTK 7.0 accomplishes a very specific task of applying a 4x4 transformation to a VTK 2D surface. This is followed with an Interative Closest Point (ICP) fusion with a target surface. The point data scalars are transferred from the source to the target. 

Inverts a 4x4 landmark transformation, applies to VTK polydata and then performs affine ICP. Scalars are transferred
