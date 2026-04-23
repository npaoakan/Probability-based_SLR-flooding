This script models static sea-level rise (SLR) inundation for the Hawaiian Islands using a probability-based framework that accounts for both DEM vertical uncertainty and water surface uncertainty. For each SLR increment (0–10 ft), it computes flood depth surfaces using a tidal datum-corrected water surface (TCARI MHHW), classifies inundation into Surficially Connected Inundation (SCI) and Topographically Isolated Inundation (TII), and outputs reclassified flood depth rasters and extent shapefiles. Built with ArcPy, NumPy, and SciPy for use in coastal hazard assessment and climate adaptation planning in Hawaiʻi.



Inputs required:

* A digital elevation model and its vertical uncertainty.
* A water surface and its vertical uncertainty. You may also use a single value (e.g., MHHW) and its standard deviation as vertical uncertainty.
* Amount of SLR to be modeled.



NOTE: the Oahu-specific script was created to incorporate spatial analyses of compromised drainage systems and flooded streets.

