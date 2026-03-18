📘 Purpose of decagon_projection_properties.json
The file decagon_projection_properties.json contains a structured description of two fundamental geometric ideas used in the project:

How the decagon can generate meaningful rectangles  
(specifically the relationship between the radius 
𝑟
 and the second diagonal 
𝑑
2
).

How certain special projections of the icosahedron preserve the proportion

𝑑
2
𝑟
=
𝜑
The purpose of decagon_projection_properties.json is to serve as formal documentation, a theoretical reference, and a foundation for future algorithms that rely on these geometric relationships.

📂 What decagon_projection_properties.json contains
1. decagon_as_rectangle_generator
This section explains how selecting specific pairs of decagon vertices allows the construction of a rectangle where:

the long side corresponds to the second diagonal 
𝑑
2
,

the short side corresponds to the radius 
𝑟
.

It also clarifies that this correspondence is not universal for arbitrary projections.
It only holds in certain projection planes of the icosahedron — specifically those that contain the “hidden decagons” embedded in its symmetry.

2. proportion_preservation_in_special_projections
This section describes why the proportion 
𝑑
2
/
𝑟
=
𝜑
 is not preserved under general 3D→2D projection, but is preserved under:

orthogonal projection,

onto planes that contain icosahedral symmetries,

especially the planes where the regular internal decagons lie.

This explains why the projected decagon can be used as a reliable geometric template for constructing or analyzing the icosahedron.
