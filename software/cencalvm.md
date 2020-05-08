# cencalvm

C++ library with C and Fortran interfaces for querying 08.3.0 and
earlier versions of the USGS San Francisco Bay region seismic velocity
model. The seismic velocity model is encoded using the binary [Etree
format](http://www.cs.cmu.edu/~euclid/). 

**Important**: The Euclid library running on big endian machines
  cannot read the Etree files for models (e.g., 08.3.0) created on
  little endian machines.

## Quick Links

* [GitHub repository](https://github.com/usgs/earthquake-cencalvm)
* [Documentation](https://usgs.github.io/earthquake-cencalvm)
* Binary packages
  - [Linux](https://github.com/usgs/earthquake-cencalvm/releases/download/v1.1.0/cencalvm-1.1.0-Linux-x86_64.tar.gz)
  - [MacOS](https://github.com/usgs/earthquake-cencalvm/releases/download/v1.1.0/cencalvm-1.1.0-Darwin-x86_64.tar.gz)
* [Source code](https://github.com/usgs/earthquake-cencalvm/releases/download/v1.1.0/cencalvm-1.1.0.tar.gz)
