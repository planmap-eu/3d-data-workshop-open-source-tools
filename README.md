# 3d-data-workshop-open-source-tools

The workshop will focus on three-dimensional data as point clouds and 3d meshes and their use for scientific application. We will provide a simple overview of several (very basic) open source packages that can be used for the management, exploitation and visualization of different data types.

## Indicative programme
 The workshop will require 2:00 hours. At the end tutors will be available for the interested ones willing to delve into more details.

1. Introduction:
    - Basics of three-dimensional data: from point clouds to structured data
    - Inherent issues for data management, the nearest nieghbor problem. peek inside out-of-core visualization and Level of Details techniques. Large coordinates rounding problems to keep in mind
    - Lines, surfaces and volumes meshes and their use in geosciences (vtk/paraview oriented)

2. Tutorials
    - Point cloud data / meshes in CloudCompare, and overview of tools and plugins. During this exercise we will try to perform a geological interpretation on a Virtual Outcrop. We will then see how the data can be exported and analyzed.
    - Python for 3d data management and visualization. Overview of libraries. Loading the data in jupyter, best fitting planes calculation (+ possibly evaluating the goodness of fit) and scatterplot plotting. Computing scalars on a 3d model (e.g. distance from a plane). Generation of vtk files for paraview visualization.
    - Creatione of publication quality 3d scene in paraview. Loading the 3d model, adding information using glyphs and scalar fields visualization from the data previously generated.
    - OPTIONAL: Rendering of the scene in Blender.
