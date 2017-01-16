# Landmark transformation and ICP

This software written in C++ with VTK 7.0 API and accomplishes a very specific task of applying a 4x4 transformation to a VTK 2D surface. This is followed with an Interative Closest Point (ICP) fusion with a target surface. The point data scalars are transferred from the source to the target. 

# Use case 
The need for this software arose for recovering the inverted transformation from a transformation available to go from target surface to source, instead of source to target. 

## Author
**Rashed Karim**

Biomedical Engineering

King's College London 
