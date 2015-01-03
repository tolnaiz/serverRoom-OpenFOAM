serverRoom-OpenFOAM
===================

OpenFOAM data center room project for my MSc thesis

Requirements
------------

OpenFOAM > 2.3.0

swak4Foam > 0.31

Gmsh > 2.8



Running the case
----------------

I cannot upload the mesh files because of Github's quota, so you need to generate the mesh file for yourself.
You need to generate the mesh in Gmsh, then convert it to OpenFOAM with the gmshToFoam command.

After it completes, you can run the parallel case with ./Allrun
