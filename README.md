Geomeppy 3D Viewer
================

Geomeppy 3D Viewer is an engine to visualize 3D EnergyPlus models online.

It is a fork of Viktor Kovacs' brilliant [Online 3D Viewer](https://github.com/kovacsv/Online3DViewer), extended to accept EnergyPlus IDF files as input.

Supported file formats:
  - idf
  - 3ds (with textures)
  - obj, mtl (with textures)
  - stl (ascii and binary)

Website
-------

- You can open 3D files in three ways:
  - Use the open button from the top menu.
  - Drag&Drop files to your browser.
  - Define file urls as location hash.
- You should open the main file, and all of its requested files.
  - For example open the requested mtl file with an obj file,
  - or open textures with 3ds file.

Embeddable
----------

This is the embeddable version of the viewer:
- In this case you should host the 3D models.
- See examples for more information.

Wiki Extension
--------------

This is a WikiMedia extension for viewing 3D models. It is in experimental phase currently.
