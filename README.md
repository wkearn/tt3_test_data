# Test data for TopoToolbox

If you are looking for the digital elevation models used in TopoToolbox documentation and examples, check out the [TopoToolbox/DEMs](https://github.com/TopoToolbox/DEMs) repository.

This repository provides digital elevation models and derivative products for snapshot testing of TopoToolbox.

Data are stored as GeoTIFFs and managed using [Git Large File Storage](https://git-lfs.com/). If you clone this repository without Git LFS installed on your computer, you will not receive the data, but pointers to the GeoTIFF files stored on GitHub.

Snapshot datasets are located in subdirectories within this repository. The original digital elevation model should be stored in a file called `dem.tif`. Derivatives of this DEM are created by an automated MATLAB test script in [TopoToolbox/topotoolbox3](https://github.com/TopoToolbox/topotoolbox3) and have names derived from the functions used to create them.
