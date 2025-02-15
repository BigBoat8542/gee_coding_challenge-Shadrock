# First Visualization and Analysis in GEE
In this tutorial, you'll learn how to generate an animated GIF representing 20-year median NDVI for serial 16-day MODIS composites spanning January 1st through December 31st. The tutorial uses [MODIS](https://modis.gsfc.nasa.gov/), a moderate resolution satellite, and [NDVI](https://en.wikipedia.org/wiki/Normalized_difference_vegetation_index), which is a common reflectance-based vegetation index. The [Earth Engine Data Catalog](https://developers.google.com/earth-engine/datasets/) provides NDVI as a precalculated [dataset](https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MOD13A2) for convenience.

## Instructions

Follow the [MODIS NDVI Times Series Animation tutorial on the GEE community web site](https://developers.google.com/earth-engine/tutorials/community/modis-ndvi-time-series-animation) or the GEE [Github repository of the same tutorial](https://github.com/google/earthengine-community/blob/master/tutorials/modis-ndvi-time-series-animation/index.md). That tutorial will walk you through your first NDVI visualization!

# Coding Challenge
Once you've completed the NDVI tutorial, write a script for GEE that will create the same output (an animated .gif) for a specific country. Choose any country you like. Once completed, copy the code from your GEE file into a `.js` file and place it in a new Github repo. Place your animated `.gif` in the same repo and embed it in your `README`. You will submit a link to your repo containing the code, your animated gif, and a brief write-up in your `README` about the country you selected and any observations you have. Your output should look something like this (I chose Kenya):
> ![NDVI Animation of Kenya](images/NDVI_animation_KE.gif)

## What are these animations showing, exactly?  
NDVI is mapped to a color gradient from tan to dark green representing low to high photosynthetic capacity (low to high vegetation cover density/productivity). The tide-like latitudinal shift in vegetation is associated with the sun’s declination moving between 23.5&deg; north and 23.5&deg; south, relative to the equator, throughout the year. See [Nicholson, 2019](https://journals.ametsoc.org/doi/full/10.1175/BAMS-D-16-0287.1) for more information on this phenomenon. Similar seasonal patterns of vegetation productivity are found around the world at both small and large scales.


Luke Response:
A brief (250 - 500 word) write up about the country you choose and any observations you have based on your output.

> Although this GIF generated by Eswatini is not time-stamped in a series graph, we can see how NDVI throughout the small landlocked nation has dramatic shifts in the lapse. The dark green values, imply strong vegetation health, green values healthy vegetation and yellow/white is weak vegetation health. In Eswatini, a country less than 7000 miles squared, it is an interesting case study because of small landlocked nations. According to the food and agricultural organization, Eswatini's traditional economy thrives on agriculture, selling sugar cane and other products. At the beginning of the GIF, presumably January, we see extremely strong NDVI values suggesting this is the time of year when the growth is very strong, however towards summer months in the middle of the year, there is a heavy drop off, with nearly all light green values and some yellow/white spots, suggesting that agricultural yields then may suffer due to the season, drought, or more factors during this time period. This is useful information since we see many other Sub-saharan African countries experience these swings in agricultural yields, and vegetation over time, and with Saharan nations being consistently low in NDVI values. 

Eswatini however with its consistently strong NDVI values suggests this is a climate and region favorable for agriculture. Vegetation health does appear to be very strong in Eswatini, suggesting it's a favorable place to expand sugar cane and other important regional crops. NDVI over time in Eswatini is overall pretty strong, making it a unique region, and potentially prosperous in the future around vegetation.
