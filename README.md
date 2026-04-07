# PySPLIT-Argentina
Adapted PySPLIT workflows for trajectory visualization. This repository extends the original PySPLIT functionality to enable geographic plotting, altitude-based coloring, and integration with GeoTIFF base layers, providing enhanced visualization for back trajectories and plotting altitude vs time.

Features
Trajectory Visualization: Plot back trajectories directly on maps using Cartopy with Plate Carrée projection.
Altitude-Based Coloring: Automatically assign colors to trajectories based on initial altitude levels.
GeoTIFF Base Layers: Overlay trajectories on custom base maps (e.g., Natural Earth GeoTIFFs) for context.
Shapefile Integration: Add boundaries, sites of interest, and other vector layers to maps.
Time Series Plots: Generate Altitude vs Time charts for trajectory analysis.
Customizable Maps: Control map extent, gridlines, labels, and other cartographic elements.
Installation
Clone the repository:
git clone https://github.com/yourusername/pysplit-cartopy.git
Install required Python packages (recommended in a virtual environment):
pip install numpy pandas matplotlib cartopy rasterio geopandas
Usage
Prepare your PySPLIT trajectory objects (trajgroup).
Set map boundaries and altitude color mapping.
Use the provided plotting routines to visualize trajectories on Cartopy maps.
Optionally, plot Altitude vs Time charts using the included scripts.
Integrate GeoTIFF or shapefiles for enhanced geographic context.
Example

This repository does not include PySPLIT itself. It extends PySPLIT output by adding altitude vs. time charts for back trajectories. Original PySPLIT code was created and maintained by Mellissa S. C. Warner (GitHub: mscross) as an open-source toolkit for HYSPLIT trajectory analysis.


