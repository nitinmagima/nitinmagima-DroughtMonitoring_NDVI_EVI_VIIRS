# Drought Monitoring Using NDVI and EVI Using VNP13A1: VIIRS Vegetation Indices 16-Day 500m

Author - Nitin Magima

Date - Feb 2024

Version - 1.0

The jupyter notebook aims to generate seasonal anomaly maps for each n-day period of the rainy seasons in a country. It uses VIIRS product #13, Gridded Vegetation Indices (VNP13 Level 3 suite). The level 3 gridded vegetation indices are standard products designed to extend the significant VI time series derived from AVHRR and MODIS (Huete et al. 2002). The level 3 spatial and temporal gridded vegetation index products are composites of daily surface reflectances. They are generated at 500m, 1km, and 0.05o (~5.6km) every 8 days (quasi), 16 days, and calendar month. 

The standard Normalized Difference Vegetation Index (NDVI), referred to as the “continuity index” to the existing NOAA-AVHRR and MODIS derived NDVI. At the time of S-NPP launch S-NPP VIIRS VI User Guide-V2.1.1 8  (2011) there was nearly a 30-year NDVI record from AVHRR and MODIS (1981- and 2000-). VIIRS NDVI will extend this long term data record for use in operational monitoring studies.

The enhanced vegetation index (EVI) was developed to optimize the vegetation signal with improved sensitivity in high biomass regions and improved vegetation monitoring through a de- coupling of the canopy background signal and a reduction in atmosphere influences (Huete et al. 1997; Huete et al. 2002). 

Google Earth Engine (GEE) is a web platform for cloud-based processing of remote sensing data on a large scale. The advantage lies in its remarkable computation speed as processing is outsourced to Google servers. The platform provides a variety of constantly updated datasets; no download of raw imagery is required. While it is free of charge, one still needs to activate access to Google Earth Engine with a valid Google account.


DISCLAIMER

This is a set of scripts  shared for educational purposes only.  Anyone who uses this code or its
functionality or structure, assumes full liability and credits the author.

Map Disclaimer

The designations employed and the presentation of the material on this map do not imply the expression 
of any opinion whatsoever on the part of the author concerning the legal status of any country, territory, city or area or of its authorities, or concerning the delimitation of its 
frontiers or boundaries.

Sources
- [LANDDATAOPERATIONALPRODUCTSEVALUATION MODIS/VIIRS LAND PRODUCT QUALITY ASSESSMENT](https://landweb.modaps.eosdis.nasa.gov/browse?sensor=VIIRS&sat=SNPP)
- [Vegetation Index Product Suite User Guide & Abridged Algorithm Theoretical Basis Document](https://lpdaac.usgs.gov/documents/1372/VNP13_User_Guide_ATBD_V2.1.2.pdf)