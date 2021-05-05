# geomodelgrids

C++ applications and C++ library with C interface for managing and querying
georeferenced 3D gridded data stored using HDF5. Python interface for
creating models.

21.0.0 and later versions of the USGS San Francisco Bay region seismic
velocity model use this interface.

## Features

* Store models using a self-describing, portable, widely-used storage scheme, HDF5.
* Support variable resolution models with and with out topography.
* Serial query interface only loads a portion of the model into
memory.
* Use caching to improve query speed.

## Quick Links

* [GitHub repository](https://github.com/baagaard-usgs/geomodelgrids)
  * Source code
  * Bug reports
  * Feature requests
* [Documentation](https://baagaard-usgs.github.io/geomodelgrids)
* [Releases](https://github.com/baagaard-usgs/geomodelgrids/releases)
  * Source code for releases
  * Binary packages for MacOS and Linux
