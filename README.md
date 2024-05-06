# gridinit

Small python tool to generate typical geospatial grids for sea ice remote sensing.

## Scope

The purpose of `gridinit` is to generate geospatial grids in a reproducible way. 
The implementation is driven by the specific needs of the
[pysiral project](https://github.com/pysiral) and errors might occur 
for more general geospatial grid applications. This 
project is optimized for:

- polar projections with roughly equal area grids 
  (Lambert Azimuthal Equal Area or Polar Stereographic)
- isotropic resolution
- Extent in x and y direction is a multiple of the spatial resolution

## Installation

Integration into the Python Package Index (PyPi) is currenlty not on the agenda. 
The `gridinit` package should therefore be installed directly from git 

```commandline
pip install git+https://github.com/pysiral/gridinit
```

or with full developer packages:

```commandline
pip install git+https://github.com/pysiral/gridinit[dev,tests]
```



## Usage

See the [folder with example notebooks](https://github.com/pysiral/gridinit/tree/main/examples)
for a tutorial of the functionality. 
