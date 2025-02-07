# Earth Engine to GeoTIFF

A simple Python script to download a map from Google's Earth Engine and save as a GeoTIFF file.

The script will download an RGB image from the Sentinal S2 Surface Reflectance satellite, but this could be changed fairly easily by modifying the ImageCollection in EarthEngineToGeoTIFF.py.

See [this blog post](https://sites.northwestern.edu/researchcomputing/2021/11/19/downloading-satellite-images-made-easy/) for a description of the code and how to use it. 

___
*2025 update*: Note that the COPERNICUS/S2_SR asset in Earth Engine is deprecated.  My code still works as it did when I wrtoe it in 2021, but mit ay break at a later date if Earth Engine removes this asset.  And of course there are probably better assets to choose from now!