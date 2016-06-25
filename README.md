# FEM
Source code for FEM computing


<h2> Domain</h2>
L-shaped domain $(0,2)\time (0,2) \setminus [1,2]\times [1,2]$
<ul>
<li> L_uniform_init_type_1.msh (See mesh sample in L_uniform_init_type_1.png)
<li> L_uniform_init_type_2.msh (See mesh sample in L_uniform_init_type_2.png)
<li> L_uniform_init_type_3.msh (See mesh sample in L_uniform_init_type_3.png)
</ul>

<h3>How to use the mesh</h3>

In command line mode, run "gmsh refine xxx.msh" to refine the mesh by splitting the current elements. Then you can get
uniform triangulation of L-shaped domain.

A sample mesh from mesh refinnig the L_uniform_init_type_3.msh is as follows.

<img src="https://github.com/xfliu/FEM/blob/master/L_uniform_init_type_3_dense_mesh.png">


<hr>
