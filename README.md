# Glasgow-Flooding

The project sought to visualise how Glasgow's communities are affected by current and future flooding.

## Process

### 1. Mapping Glasgow's Data Zones

Scotland uses the Scottish Index of Multiple Deprivation (SIDM) to measure holistic deprivation across multiple domains. I downloaded the 2020 data from the SIMD website (https://simd.scot/#/simd2020/BTTTFTT/9/-4.0000/55.9000/), which I then imported into QGIS. I filtered for areas which were under the Glasgow City Council, resulting in the current map.

### 2. Mapping Flooding

I then downloaded flooding data from the Scottish Environmental Protection Agency (SEPA) (https://www2.sepa.org.uk/flooddata/). I then cropped the various layers to the boundaries of the data zones and coloured them based on the symbology provided by the SEPA.

### 3. Creating the Maps

For the PDF map layout, I chose to exclude surface water and small watercourses flooding as the polygons were too numerous and small to be meaningfully visible. I also chose to colour the data zones using the orange colour ramp as it provided a good contrast with the river and coastal flooding layers. For the web map, I chose to use a black-white colour ramp for the data zones as it provided by the best contrast with all three layers.

## Reflections

### Analysis

From the map, it does appear that data zones do seem to be more affected by flooding. However, further comparative analysis is needed to conclusively establish this claim (e.g. Calculating and comparing the area of each data zone affected by flooding). 

### Areas for Improvement

As stated above, there could be a much more conclusive way of analysing the correlation between a data zone's SIDM ranking and its flood risk. Currently, the only way to analyse this correlation is based off looking at the map, which is not a robust method of analysis.

There could be a much more clearer way of showing surface flooding. Currently, the layer appears cluttered and messy, with the polygons being too small and numerous to be meaningfully visible without zooming in. Admittedly, I don't have a solution to this problem, but it is definitely an area to improve on.
