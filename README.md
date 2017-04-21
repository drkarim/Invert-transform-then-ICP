# Landmark transformation and ICP

This software written in C++ with [VTK API](http://www.vtk.org/doc/nightly/html/index.html) and accomplishes a very specific task of applying a 4x4 transformation to a VTK 2D surface. This is followed with an [Iterative closest point (ICP)](https://en.wikipedia.org/wiki/Iterative_closest_point) fusion with a target surface. 

After application of the transformation matrix, the point data scalars are transferred from the source to the target. 

# Use case 
The need for this software arose for recovering the inverted transformation from a transformation available to go from target surface to source, instead of source to target. 



## Author 
```
Dr. Rashed Karim 
Department of Biomedical Engineering 
King's College London 
```
