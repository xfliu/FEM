# FEM
Source code for FEM computing


<h2>Uniform mesh for an L-shaped domain</h2>
<a href="http://gmsh.info/">Gmsh</a> file for  triangulation of L-shaped domain: 

![equation](http://www.sciweavers.org/tex2img.php?eq=%280%2C2%29%5Ctimes+%280%2C2%29%5Csetminus+%5B1%2C2%5D%5Ctimes+%5B1%2C2%5D&bc=White&fc=Black&im=png&fs=12&ff=arev)

<ul>
<li> L_uniform_init_type_1.msh
<li> L_uniform_init_type_2.msh
<li> L_uniform_init_type_3.msh
</ul>

<img src="https://github.com/xfliu/FEM/blob/master/sample_of_initial_mesh.png">

<h3>How to use the mesh</h3>

In command line mode, run "gmsh refine xxx.msh" to refine the mesh by splitting the current elements. Then you can get
uniform triangulation of L-shaped domain.

A sample mesh from mesh refinnig the L_uniform_init_type_3.msh is as follows.

<img src="https://github.com/xfliu/FEM/blob/master/L_uniform_init_type_3_dense_mesh.png" width="500px">


<hr>
