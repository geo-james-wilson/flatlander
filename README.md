# flatlander
Tools to extract flat lands

The inspiration for this toolkit comes from the topography of Florida, particularly with respect to paleoshorelines such as the Trail Ridge, which shows evidence of relative uplift in the central part of the state. Flanking the ridge are broad, relatively flat regions. The goal of this project is to extract these flat regions in order to compute spatial statistics and look for additional clues to the geologic history of Florida.

Brain storming
1) Create toy raster datasets for unit testing
2) Prototype code using convolutions to do edge detection to delineate regions of interest
3) Download SRTM, ASTER, LiDAR or other DEM raster
4) Design and evaluate various filters and rules to delinate the regions
5) See where the data leads you
6) Evaluate clumping algorithms to merge like regions together
7) Implement visualization tools from histograms to cross sections
8) Evaluate statistical metrics such as median, mean, range, standard deviation or other metrics to characterize homo/heterogeneity across the landscape
9) Consider masking out rivers or using them to merge adjacent regions
