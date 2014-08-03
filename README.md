blender_XYZ_surface_presets
===========================

Library of parametric surface functions for the blender Extra Objects add-on.

The Extra Objects add-on for [Blender](http://www.blender.org/) has a `Add> Mesh> Extra Objects> Math Function > XYZ Math Surface` that is defined by three parametric equations. The [documentation page](http://wiki.blender.org/index.php/Extensions:2.6/Py/Scripts/Add_Mesh/Add_3d_Function_Surface) has a number of example surfaces, but there are a lot more interesting named surfaces about.

Its fairly easy to enter any formulae you find for a parametric 3D surface into Blender and save it as an `Operator Preset`. This is my collection of such presets. I haven't included every named surface out there, just ones I think might make interesting images. You can see a couple of examples at my [look think make](http://elfnor.com/parametric-surfaces-in-blender.html) blog.

You need to download and unzip the repository, then copy the python files in it to the right place in your Blender install. Working out the right place can take some messing around. Here's how I did it. First enable the Extra Objects add-on under `File > User Preferences> Addons`). Then add  the default math surface to your blend file `Add> Mesh> Extra Objects> Math Function > XYZ Math Surface` and then save it as a preset (using the `+` button beside `Operator Presets`) to a unique name (say `shell`) and then search your hard drive for the file `shell.py`. Place all the downloaded python files in the same place as `shell.py`. On my Linux mint install the correct directory was `~/.config/blender/2.71/scripts/presets/operator/mesh.primitive_xyz_function_surface/`. 

Current presets available in this repository:

*  bonbon
*  boy
*  catalan
*  catenoid
*  clifford torus
*  cochlea
*  cosinus
*  dini
*  enneper
*  helicoidal
*  helix
*  hexahedron
*  hyperhelicoidal
*  klein
*  moebius
*  pseudo catenoid
*  pseudosphere
*  ridged torus
*  shell
*  sine
*  snake
*  stereosphere
*  torus
*  twisted torus

 



