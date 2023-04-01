# Night-Time-Lights
This repository contains code developed by Somdeep Kundu, PGD NHDRM 2022-23, Indian Institute of Remote Sensing, Dehradun, to visualize developmental changes using Night Time Light (NTL) data. The code is written in Google Earth Engine, and uses monthly average radiance composite images obtained from the Visible Infrared Imaging Radiometer Suite (VIIRS) Day/Night Band (DNB) to visualize changes over time. The visual parameter used in this repository is from red to blue, where red indicates older developments, and blue indicates newer ones.

The NTL data used in this repository is VIIRS Stray Light Corrected Nighttime Day/Night Band Composites Version 1. Due to the nature of monthly composites, it is not always possible to obtain good quality data coverage for a given month, especially due to cloud cover and solar illumination. Therefore, it is recommended that users of these data utilize the 'cf_cvg' band to determine cloud cover, and not assume a value of zero in the average radiance image means that no lights were observed.

It should be noted that the Version 1 of the NTL data used in this repository has NOT been filtered to screen out lights from aurora, fires, boats, and other temporal lights. This separation is under development and will be included in a later version of this time series. In addition, there are artifacts introduced due to the correction procedure used in twilight regions. These are discussed in detail in the reference paper, which can be accessed through the link provided.

This repository contains code to generate a visualization of the NTL data, and also includes a classification legend using ui.Panel. The repository can be useful for researchers and analysts working on developmental changes, and for policymakers who need to monitor urbanization and associated environmental impacts.

For more information about the NTL data, and the code in this repository, please refer to the code documentation and comments.
