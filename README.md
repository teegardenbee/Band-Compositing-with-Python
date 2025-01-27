# Band-Compositing-with-Python

A "Band Composite" refers to the process of combining multiple individual bands (separate images representing different wavelengths of light) from a multispectral image into a single image
This script uses the Rasterio python library which is bascially a python extension for GDAL.
In this code, An RGB ortho is being composited with a dem ortho. Which means there will be a 4th band added to each the ortho which will show the elevation of any particular pixel in the ortho.
