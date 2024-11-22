# Exploring Data and Mapping the Thomas Fire Scar through False Color Imagery

Purpose: This repository has two notebooks, `..fire-perimeter` and `..fire-scar`. The Fire Perimeter notebook shows basic techniques to read in and work with shapefiles in Python, and the Fire Scar notebook shows how to combine that shapefile with, in this example, raster data from the Landsat satellite. This repository also explores the Landsat data, and shows how to adjust this data's color bands to create a false color image. In this example, the shapefile is a boundary of the 2017 Thomas Fire, and the raster data from Landsat is an image of the Santa Barbara County area, containing visible, infrared, and near infrared color bands.

Landsat data was retrieved from: https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2
Thomas Fire scar data was retrieved from: https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436

The Thomas Fire data came from a much larger dataset, and was filtered to create a new shapefile of only the Thomas Fire. See the `..fire-perimeter` notebook for more! Also see this repository for information on how to load in this data properly. 

This repository was an assignment from the MEDS class EDS 220 in the Fall of 2024. 
See the assignment and course website here: https://meds-eds-220.github.io/MEDS-eds-220-course/assignments/assignment4.html



