.. _OpenSceneGraph: https://github.com/OpenSceneGraph/OpenSceneGraph
.. _osgEarth: https://github.com/gwaldron/osgearth
.. _SIMDIS: https://simdis.nrl.navy.mil
.. _Pelican Mapping: http://www.pelicanmapping.com
.. _Read the Docs site: http://emminizer-testing.readthedocs.io/en/latest/
.. |docs| image:: https://readthedocs.org/projects/emminizer-testing/badge/?version=latest
    :alt: Documentation Status
    :scale: 100%
    :target: http://emminizer-testing.readthedocs.io/en/latest/

**********
SIMDIS SDK
**********

|docs|

..
   contents::
   :maxdepth: 2

Introduction
============

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

The SIMDIS SDK provides support for loading all 3D model formats supported by
OpenSceneGraph_ (OpenFlight, 3D Studio, Wavefront OBJ, etc), loading the
SIMDIS .db Terrain and Imagery files, and streaming terrain and imagery data
from the ReadyMap server product developed by `Pelican Mapping <http://www.pelicanmapping.com>`_ using osgEarth_.

Documentation
=============
You can find documentation for the SIMDIS SDK on the `Read the Docs site`_.
