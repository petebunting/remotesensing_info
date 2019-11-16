title: Introduction to RSGISLib
slug: eo
category: Earth Observation
tags: Python, RSGISLib, Image Processing.
date: 2019-11-15
modified: 2019-11-15

## Introduction

The Remote Sensing and GIS Software Library [RSGISLib](https://www.rsgislib.org) is primarily developed and supported by Pete Bunting and Dan Clewley; it was initially developed to provide the functionality we required for our research where it wasn't available in existing software packages. However, RSGISLib has evolved into a set of Python modules providing a wide range of functionality which is scriptable, creating a flexible system for data analysis and batch processing. The available modules are:

* Image Calibration
* Classification
* Elevation
* Image Calculations
* Image Filtering
*  Image Morphology
* Image Registration
* Image Utilities
* Histogram Cube
* Raster GIS
* Image Segmentation
* Tools
* Vector Utilities
* Zonal Statistics

For installation of the RSGISLib software and tools please see the [Software Page](/software).

### Other Software Tools

Alongside RSGISLib we use other tools, such as the [GDAL](https://www.gdal.org) software, KEA file format and TuiView image viewer. 

#### GDAL


#### The KEA File Format
The KEA file format developed by \citet{BuntingGillingham2013} and named after the New Zealand bird (Kea) is a HDF5 based image file format with a GDAL driver. Therefore, the format can be used in any software using GDAL, provided the KEA library is available. It offers support for large raster attribute tables and uses zlib based compression to provide small file sizes. The development was funded and supported by Landcare Research, New Zealand.

#### TuiView
TuiView is an open source viewer for remote sensing data, named after the New Zealand bird (Tui). Although primarily for viewing raster data but it will also display vectors. One of the main advantages of TuiView is it has a lot of functionality for viewing and manipulating Raster Attribute Tables (RAT), which the object-based classification within RSGISLib is build on top of. TuiView is cross platform and provides a consistent interface across Windows, Linux and Mac platforms. It is capable of handling very large datasets, providing overviews are generated.


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwMTk1NTI4NjgsMTE0NzExNTAxNF19
-->