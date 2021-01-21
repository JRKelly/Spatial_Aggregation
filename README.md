# Spatial_Aggregation
Scripts for the Creation and Spatial Aggregation of Pseudo-Datasets

*Aggregate Random Points to Census Polygons* -- (arcpy) assigns pairs of random values to points in a randomly located point feature class and then aggregates by spatial join to census block group, tract, county and state polygons.  Evaluates and collects Moran's I, mean and standard deviation, and Pearson's R at each level of aggregation.  
