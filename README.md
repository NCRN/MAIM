# MAIM
This project produced a spatially explicit computational model (termed the Marsh Accretion and Inundation Model (MAIM)) and model results predicting the impact of user-defined sea level rise scenarios on vegetation. The model takes as input detailed (1-m resolution) map layers representing elevation (generated from LiDAR) and initial vegetation classification. Vegetation classes are constrained to individual elevation ranges, predetermined based on NPS vegetation maps, plot inventory data, and digitalization of aerial photography. Uncertainty in these elevation ranges is represented through 100 Monte Carlo permutations of the vegetation class elevation boundaries. As sea level rise progresses, the model identifies where vegetation classes will become unsuitable for their location, and adjusts the map accordingly
