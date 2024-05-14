# Salome_BCC_UnitCell_Periodic-mesh
Periodic Mesh Generation of BCC Lattice Materials using SALOME for FEM Analysis

# Description:
BCC lattice materials made up of unit cells are among the most popular lattice structures in engineering. Different dimensions of these BCC lattice structures are shown in the figure below.

<img width="700" alt="t1" src="https://github.com/Sina-Taghizadeh/Abaqus_BCC_UnitCell/assets/162900845/59ae7570-f236-4451-8842-e30226199b60">

For FEM analysis of these structures, we need their geometrical model in a CAD software and meshing of their geometry. Also, for analyzes such as multiscale or homogenization analyzes, we need to have periodic or Cyclic meshes and boundary conditions so that for each node on one side of the boundary, there is exactly a corresponding node on the opposite boundary. As an example, the figure below shows two corresponding planes whose meshes are fully matched node to node.

<img width="300" alt="t1" src=https://github.com/Sina-Taghizadeh/Salome_BCC_UnitCell_Periodic-mesh/assets/162900845/1cb98190-c1a7-48f8-81bd-fc4e7c2d8ffd>

With the help of dear Franco, In this project, I have designed the geometrical model of the BCC unit cell and meshed it periodically in SALOME software. I have also modularized its script for different dimensions of unit cells and uploaded it to this repo. The figure below shows this unit cell along with its mesh.

<img width="300" alt="t1" src=https://github.com/Sina-Taghizadeh/Salome_BCC_UnitCell_Periodic-mesh/assets/162900845/6477db84-99dd-4972-9d0e-f0256e644429>

# How to use:

**1) Open the BCCUCPM.py file and replace the current directory address with your own directory address on lines 15 and 316 (optional).**

**2) On lines 28 to 37, replace the specifications of the BCC unit cell you have in mind, including radios of strut, length of cube, Length Discretization and other items, with the values written.**

**3) Then run SALOME and click on the Load Script option from the file tab and select the BCCUCPM.py code in the repo.**

# Collaboration:

I would be happy if anyone has any ideas for improving this project and expanding the current project.

sina.taghizadeh123@gmail.com
