.. Save As SVG Documentation master file

.. toctree::
   :maxdepth: 2

#####################
Save As SVG App Store
#####################

SVG Main Entry
**************


.. role:: yellow-bold
.. role:: green-bold
.. role:: cyan-bold
.. role:: blue-bold
.. role:: magenta-bold
.. role:: white-bold
.. role:: grey-bold
.. role:: black-bold

**Note**: This is the Mac OS release of Save As SVG.  For the Windows release, click Win64 near the top of the page 
(under our logo, where it says OS).

|
**Save As SVG** is a powerful Autodesk Fusion 360® add-in that allows users to export sketches as SVG files. 

Key Features and Functionality
==============================

**Core Functionality**: 
  It takes any sketch created within Fusion 360 and converts it into a Scalable Vector Graphics (SVG) file.
**Versatile Applications**: 
  The exported SVG files can be used for various purposes, including laser cutting, CNC milling, or other 
  applications that require vector-based graphics.
**Ease of Use**: 
  After creating and finishing a sketch, users simply right-click on the sketch in the browser tree and 
  select the "Save to SVG" option.
**Customization Options**: 
  Users can modify the line weight and colors for lines representing the different sketch profile types 
  within the exported SVG. Available colors include :yellow-bold:`Yellow`, :green-bold:`Green`, 
  :cyan-bold:`Cyan`, :blue-bold:`Blue`, :magenta-bold:`Magenta`, :white-bold:`White`, :grey-bold:`Gray` 
  and :black-bold:`Black`.
**Face Filling**: 
  The plugin offers a "Fill Faces" option, which, when enabled, fills the enclosing faces of a sketch using 
  the selected color settings for perimeter, cutouts, or inset.
**Scale and Compatibility**: 
  By default, the plugin creates SVG files at a standard 96 DPI (dots per inch), matching the scale used by 
  Fusion 360, modern applications and browsers. For compatibility with older applications like Adobe 
  Illustrator or Vectric VCarve Pro, a **Scale** option is provided with alternate DPI settings.
**Beyond Simple Sketches**: 
  The plugin handles complex sketches, which may not contain closed loop profiles, with the provided 
  **Entire Sketch** option. This option ensures that all line vectors of the sketch are included in the SVG 
  export, regardless of their geometric complexity.

In essence, the "Save As SVG" plugin bridges the gap between Fusion 360's design capabilities and the needs 
of various fabrication and design applications that utilize SVG files. 

See detailed product description here 
`Save As SVG Description <https://balunist.github.io/svg_docs2/index.html#>`__. 
See `App Store Installs <https://balunist.github.io/svg_docs2/installation/app_store.html>`__ for help with 
new or update installs.

.. note:: Save As SVG is found in the context menu of a sketch object in the browser tree.  Right-click on 
  the sketch name to see the context menu

General Usage Instructions
==========================

Starting with an existing Fusion 360 sketch in your design. The sketch can include any of supported sketch 
line types, including text objects:

- Find the sketch in the browser tree and right-click on the sketch to display the context menu.

- Select :blue-bold:`Save to SVG` and an options screen will be displayed.

- Select :blue-bold:`Sketch Profiles` for Input Type and which profiles 
  you want included, Perimeter, Cutouts and Insets, .. For the Scale, select 96 DPI, which is the
  most common scale. This should result in an SVG image size that matches the sketch size when viewed in
  a web browser.

- Select :blue-bold:`OK` and you will be prompted for a filename and save directory location.

- Select :blue-bold:`Save` and the SVG file will be created.

See `The Basics <https://balunist.github.io/svg_docs2/the-basics/index.html>`__ for an introduction to 
Save As SVG and an overview of the available features. Reading this user guide before getting started, 
will help you get the most out of Save As SVG.

For a description of the available add-in features, visit the link below.

`Save As SVG Description <https://balunist.github.io/svg_docs2/index.html#>`__

