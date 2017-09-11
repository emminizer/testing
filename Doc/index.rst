.. _OpenSceneGraph: https://github.com/OpenSceneGraph/OpenSceneGraph
.. _osgEarth: https://github.com/gwaldron/osgearth
.. _SIMDIS: https://simdis.nrl.navy.mil
.. _PelicanMapping: http://www.pelicanmapping.com

**********
SIMDIS SDK
**********

..
   contents::
   :maxdepth: 2

About
=====

The SIMDIS Software Development Kit (SDK) is an open source C++ framework
providing functionality to create 3D scenes consisting of objects, whose
position and state change with time, that are placed relative to a geographic
map.  The primary modules provided by the SDK supply functionality to manage
object position/state data, update object position/state data as time
changes, and render 3D representations of objects within a 3D scene.
Secondary modules provide utilities for parsing SIMDIS_ data files, performing
coordinate system conversions, object state vector computations, and data
metric calculations.

The intent of the SIMDIS SDK is to provide a C++ framework to be used by
third party developers to incorporate functionality similar to that provided
by the SIMDIS 3D Visualization and Analysis Toolkit within their own
applications.  The SIMDIS SDK serves as the basis for development of each
new major SIMDIS release.

The SIMDIS SDK was developed by the Visualization Systems Integration branch
of the Tactical Electronic Warfare Division at the U.S. Naval Research
Laboratory.  For more information visit:

  https://simdis.nrl.navy.mil


Installation
============
The SIMDIS SDK is provided as a package containing C++ source code for use
with Windows and Linux operating systems.  Precompiled binaries for use with
Microsoft Visual Studio have also been provided for your convenience.  See
the file [INSTALL.md](INSTALL.md) for detailed information about supported
systems/compilers, third party dependencies, and installation instructions.


Usage
=====
The SIMDIS SDK source distribution comes with a number of example programs as
well as a sample data set.  The example which illustrates the most common
usage of the SIMDIS SDK is the Platform Symbology example.  Detailed tutorials
describing SIMDIS SDK use will be added at a later date.

HTML based API documentation for the SIMDIS SDK source code can be found in
the `Doc` subdirectory.  This documentation describes the different software
components provided by the SDK.

The SIMDIS SDK provides support for loading all 3D model formats supported by
OpenSceneGraph_ (OpenFlight, 3D Studio, Wavefront OBJ, etc), loading the
SIMDIS .db Terrain and Imagery files, and streaming terrain and imagery data
from the ReadyMap server product developed by `Pelican Mapping <http://www.pelicanmapping.com>`_ using osgEarth_.

The 3D models provided with the SIMDIS SDK sample data package have all been
converted to the native OpenScenegraph .ive binary file format, which embeds
the 3D model's geometry data and associated texture files within a single,
easy to distribute file.



.. toctree::
   :maxdepth: 2
   :caption: Pages

   test



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
