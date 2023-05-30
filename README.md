# Segmenting an aereal image with SAM - Dynamic area selection

Based on the tutorial published in [segment-geospatial library documentation](https://github.com/opengeos/segment-geospatial)

This notebook presents a workflow to easily segment satellite imagery from any part of the world, by simply selecting the area in a dynamic way from a map. 
The segmentation is achieved using the Segment Anything Model (SAM) and the specific library segment-geospatial, desgined for SAM application to satellite imagery.

### Running the notebook

Given that the mask generation is a computer intensive task, it is suggestedd to run in on google collab, which will make it faster and easier.

### Application case

In this notebook, the usecase is a vineyard cropland area in Mendoza city, Argentina, which works really well given the scale related to the image resolution. However it can be easily applied to any place by just searchign for it by its coordinates and selecting it in the map with the box tool.

![](https://github.com/candepelliza/SAM_Satellite_Dynamic_Selection/blob/main/Segmentation.png)
