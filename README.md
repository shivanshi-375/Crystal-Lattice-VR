# Crystal-Lattice-VR
VR Lattice Visualization Educational Tool (Developed on Unreal Engine 5.3.2)

## Description
This tool is currently being made in collaboration with Heidi Daxberger and Alen Hadzjovic from
the Department of Environmental and Physical Sciences at University of Toronto, Scarborough
Campus.
This project's aim was to create a visualization tool for students to explore internal structures of
naturally occurring inorganic materials in an immersive 3D environment. This greatly benefits
students as it transforms their resources from an otherwise 2D projection of a 3D model as shown
below.
The 3D assets were built using Blender software which were then exported to Unreal Engine where
the main game was built.
<img width="197" alt="image" src="https://github.com/shivanshi-375/Crystal-Lattice-VR/assets/90423511/7395e65b-4a93-46f7-9ab3-bac214b12041">
<img width="213" alt="image" src="https://github.com/shivanshi-375/Crystal-Lattice-VR/assets/90423511/737ba59d-9188-48ad-b304-7a83c5f021cb">



## Features developed for the project
For this tool, I first created a space to add the molecule structures in and chose to work with a basic
unit cell of Halite (NaCl). The first goal was to be able to grab and hold the structure in VR and have
the ability to maneuver it however a student wished. Moreover, the model highlighted the internal
shapes and structures that students require to learn more about certain types of crystal lattice packing
(in this case, a face centered cubic packing with an octahedron shape)

Next, I explored different sizes of molecules and if students would benefit from being able to change
the size of the structure while visualizing it. It turned out that keeping it to one standard size and
changing information around it was more beneficial than scaling it up or down. Therefore, I created
an interface to let students change the opacity of the octahedron and be able to visualize the atom
inside the shape.

![image](https://github.com/shivanshi-375/Crystal-Lattice-VR/assets/90423511/8c4b9161-ca5a-4b83-80c7-381c9f7e9e9b)



Building onto the translucency feature, I then made it even more interactive by giving students the
ability to be able to change the visibility of the atoms in the structure. For example, you could
choose to view just the Na atoms in the unit cell, or the Cl atoms alone. There is also an
information button next to the molecule which gives you more information about the crystal
structure in a drop-down format.

To enhance readability, I added a head tracking feature to the presented information. It would
transform the information in a way, so the interface always faces the user as they walk around or
rotate the structure.

![image](https://github.com/shivanshi-375/Crystal-Lattice-VR/assets/90423511/96a4bdfd-d68e-4f99-aad9-4d1fef837906)


The final step of this tool, as it stands today, was to populate it with more molecules and structures.
I generalized it in a way that anybody can upload a new material into the tool and have all the abilities
and information about the structure. This can be done without the person having to go into the code
or have to tinker with the VR tools at all. I tested this by adding two new structures: Rutile (TiO2)
and Fluorite (CaF2).

<img width="478" alt="image" src="https://github.com/shivanshi-375/Crystal-Lattice-VR/assets/90423511/020f81f8-f352-4fbf-84f1-8d35d7cdd394">

