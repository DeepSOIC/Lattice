# What is Lattice workbench
Lattice Workbench is a plug-in module for FreeCAD.

The workbench purpose is working with placements and arrays of placements. It is a sort of assembly workbench, but with emphasis on arrays. There are no constraints and relations, there are just arrays of placements that can be generated, combined, transformed, superimposed and populated with shapes. 

Ever wondered how to create a protractor with FreeCAD? That's the aim of the workbench (including tick labeling). Also, exploded assemblies can be made with the workbench.

Additionally, the workbench features a few general-purpose tools, such as parametric downgrade, bounding boxes, shape info tool, and tools for working with compounds.

One of the big design goals of the workbench is being as parametric as possible.

# Highlights
Let's have a glance over the most important capabilities that the workbench adds to FreeCAD:

* Re-use arrays as many times as you need. Unlike Draft array, which directly generates the array of shapes, lattice array tools generate arrays of placements. These can later be populated with shapes, as many times as necessary, without having to set up another array.

* Elements of array can be different. Unlike Draft Arrays, which always generate a set of equal shapes, Lattice arrays can be used to arrange a set of different shapes. Pack the shapes to be arranged into a Compound, and use Lattice Compose feature to arrange them.

* Arrays of placements can be combined, inverted, generated from existing shape arrangements, made from individual placements, projected onto shapes, filtered, etc. This allows to produce complex arrangements without scripting.

* single placements can be used for primitive assembling of parts.

* linear arrays and polar arrays can have their axes linked to edges of shapes

* parametric explode commands allow extraction of specific elements of arrays, without losing parametric relation to the original. 

# Download/install
repository: https://github.com/DeepSOIC/Lattice

Installation: download zip, unpack the contents into a "Lattice" folder created in \Path\to\FreeCAD\Mod, restart FreeCAD. Lattice workbench was also packaged to Launchpad in the Ubuntu FreeCAD Community PPA. 

Lattice WB requires FreeCAD no less than v0.16.5155 (only available as development snapshots at the moment of writing). In earlier FreeCADs, dropdown toolbar buttons are not going to work, making many useful commands unavailable (and possibly, total inability to load the workbench). That may be fixed at some point in future.

The workbench is OS independent, it should work on any system FreeCAD can be run on. If you find that it doesn't - that is a bug. Please make an issue.

# License
Lattice workbench is licenced under LGPL V2, just like FreeCAD. For more info, see copying.lib file in the repository.

# Status
This version of the workbench is released as v1.0. So, no breaking changes will be made to it, and no new features will be added. Only bugfixes will be made. 

The development continues in another repository, Lattice2. https://github.com/DeepSOIC/Lattice2

