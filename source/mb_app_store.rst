.. MapBoards Documentation master file

.. toctree::
   :maxdepth: 2

###################
MapBoards App Store
###################

MB Main Entry
*************


.. role:: blue-bold

**Note**: This is the Mac OS release of MapBoards.  For the Windows release, click Win64 near the top of the page 
(under our logo, where it says OS).

|
**MapBoards** is a Autodesk Fusion 360 add-in designed to help with the arrangement of 3D components onto material
boards for efficient manufacturing. It can also help users generate cut lists and flat panel layouts as DXF files.


This add-in is a simpler version of MapBoards Pro, with fewer features and options. There will **NOT** be any 
further enhancements. It is intended for users who need basic functionality for arranging components and generating 
cut lists, without the advanced features of the Pro version. **There is no upgrade** to the Pro version therefore
please review the Pro version before making your purchase. For the Pro version description, 
click here: `MapBoards Pro Description <https://balunist.github.io/mbp_docs2/index.html#>`__

Key Features and Functionality
==============================

**Arrangement**:
  MapBoards (MB) automatically arranges copies of components in a 3D model onto one or more boards.
**Material Optimization**:
  MB helps determine the necessary material quantities and layout for a project.
**Export Options**:
  MB can export the arranged layouts as a simplified DXF file, suitable for cutting with laser cutters or CNC machines.
**Cut Lists**:
  MB can generate cut lists with accurate dimensions for each component, which can be used as a checklist.

See detailed product description here `MapBoards Description <https://balunist.github.io/mb_docs2/index.html#>`__
See `App Store Installs <https://balunist.github.io/mb_docs2/installation/app_store.html>`__ for help with new or update installs.

.. note:: MapBoards can be launched using the toolbar icon or from the Create dropdown menu of the design workspace.

General Usage Instructions
==========================

See `The Basics <https://balunist.github.io/mb_docs2/the-basics/index.html>`__ for an introduction to MapBoards 
and an overview of the available features. Reading this user guide before getting started, will help you get the most 
out of MapBoards.

When a project moves from the design phase to the build phase, a material estimate and layout is needed to guide the manufacturing process.
MapBoards can help with both.

Begin with your 3D model open in the Fusion 360 Design Workspace:

- Invoke MapBoard
- From the Lumber tab, update the Width and Length for each board type to match lumber dimensions available
  or that you plan to acquire
- Select the radial button on the left side of each board type to include them in the map generation
- Use the options tab to select your desired Map Output Type, Arrangement Type, Component Spacing, Board Edge, Cut List and others
- Select OK to run MapBoards to create map using copies of the components in the model

Once complete, the created map will be displayed alongside the design on the XY plane (Z up) (optionally Y up on XZ plane). The map visibility
can be controlled with the visibility icon (LightBulb) on the newly created map component. Selecting the Cut List option will create a file which can 
be used for label making or a checklist.

MB can also export maps as simplified layered DXF files for use with other CAD and CAM software. The DXF file will include component profiles and
optionally cutouts and board perimeters as separate layers.

For a description of the available add-in features, visit the link below.

`MapBoards Description <https://balunist.github.io/mb_docs2/index.html#>`__

