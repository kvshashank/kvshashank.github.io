---
layout: default
title: Research
description: 
---

# Understanding the Patterns and Drivers of Arctic Tundra Plant Communities

![test image size](./assets/images/nnet_1.png){:width="50%"}
![test image size](./assets/images/nnet_2.png){:width="45%" style="padding-bottom:60px"}

**Authors:** Venkata Shashank Konduri, [Jitendra Kumar](https://www.ornl.gov/staff-profile/jitendra-kumar), [Forrest M. Hoffman](https://www.ornl.gov/staff-profile/forrest-m-hoffman), [Verity, G. Salmon](https://www.ornl.gov/staff-profile/verity-g-salmon), [Colleen M. Iversen](https://www.ornl.gov/staff-profile/colleen-m-iversen), [Amy L. Breen](https://news.uaf.edu/expertsguide/amy-breen/), [William W. Hargrove](https://www.srs.fs.usda.gov/staff/825)  <br>
**Abstract:** The Arctic is undergoing rapid changes in climate, vegetation composition and productivity. To understand the impacts of climate change on the function of Arctic tundra ecosystems, it is crucial to understand vegetation distribution and heterogeneity across large spatial scales. Knowledge of the environmental drivers controlling current vegetation composition and distribution is necessary for modeling potential shifts under a warming climate. 

Our study was focused on three watersheds in the Seward Peninsula of Alaska, where field surveys were conducted as part of the US DOE’s NGEE-Arctic project. Using airborne hyperspectral imagery from NASA AVIRIS-NG, we developed a Deep Neural Network-based classifier to create a high resolution (5m) map of Arctic tundra plant communities with an accuracy exceeding 80%. Analysis of landscape patterns, using area and aggregation based metrics, show Alder-Willow Shrub and Tussock-Lichen Tundra communities occupy a greater proportion of the landscape and are more clumped together compared to Mesic Graminoid Herb Meadow and Sedge-Willow-Dryas Tundra communities.

We also developed an Environmental Niche Model to understand the relative importance of various environmental drivers in determining the presence/absence of plant communities. Preliminary results show that microtopography (e.g elevation) and soil moisture are the primary drivers of vegetation distribution at the landscape scale. Keystone species, like nitrogen-fixing Alder shrubs, also influence the nutrient availability and vegetation communities in their hydrologically connected downslope neighborhood. High resolution maps of plant communities will provide a better representation of above-ground trait variability in Earth System Models, and will provide data for model parameterization, benchmarking and validation. Insights from niche modeling could improve our understanding of mechanisms and environmental drivers of vegetation distribution and succession. <br>
**Slides:** [Oral presentation at AGU 2019](./slides/AGU_Presentation_2019.pdf) <br>
**Code:** [Github](https://github.com/kvshashank/Shashank_Codes/tree/master/NGEE_arctic)

<hr>

# Mapping Crops Within the Growing Season Across the United States

![test image size](./assets/images/overall_shannon.png){:width="45%"}
![test image size](./assets/images/mid-season_progression_90p_new_300dpi_2.png){:width="50%" style="padding-bottom:10px"}

**Won the 1st place poster presentation among student entries in the hydrology section of the American Meteorological Society (AMS) annual meeting 2020**  
**Authors:** Venkata Shashank Konduri, [Jitendra Kumar](https://www.ornl.gov/staff-profile/jitendra-kumar), [William W. Hargrove](https://www.srs.fs.usda.gov/staff/825), [Forrest M. Hoffman](https://www.ornl.gov/staff-profile/forrest-m-hoffman) & [Auroop Ganguly](https://coe.northeastern.edu/people/ganguly-auroop/) <br>
**Journal: Remote Sensing of Environment** <br>
**Abstract:** Timely and accurate knowledge about the geospatial distribution of crops at regional to continental scalesis crucial for forecasting crop production and estimating crop water use. The United States (US) is one of the leading food-producing countries, but lacks a nationwide high resolution crop-specific land cover map available publicly during the current growing season. The goal of this study was to map crops across the Continental US (CONUS) before the harvest, and to estimate the earliest date of classification by which crops can be mapped with sufficient accuracy (90% of full-season accuracy). The study employed a scalable cluster-then-label model that was trained on multiple years of MODIS NDVI using ground truth data in the form of US Department of Agriculture (USDA) Cropland Data Layer (CDL) products. The first step in the crop classification was to perform Multivariate Spatio-Temporal Clustering (MSTC) of annual MODIS-derived NDVI trajectories to create phenologically similar regions, or phenoregions. The second step was to assign crop labels to phenoregions based on spatial concordance between phenoregions and crop classes from CDL using Mapcurves. Assigning crop labels to phenoregions was performed within ecoregions to reduce classification errors due to spatial variability in phenology caused by variations in climate, agricultural practices, and growing conditions. The crop classifier was trained and validated on the years 2008–2014, then tested independently on 2015–2018. Ecoregion-level crop classification performed better than state-level and CONUS-level classification. Pixel-wise accuracy of classification for eight major crops by area was around 70% across the major corn-, soybeans- and winter wheat-producing areas, whereas regions characterized by high crop diversity had slightly lower accuracy. Classification accuracy for dominant crops like corn, soybeans, winter wheat, fallow/idle cropland and other hay/non alfalfa improved with time as they grew, reaching 90% of year-end accuracy by the end of August over each of the four unseen years in the test period. For corn and soybeans, the earliest dates of classification were found to be much earlier in the central regions of the Corn Belt (parts of Iowa, Illinois and Indiana) than in peripheral areas. The ability to map growing crops may permit near real-time monitoring of the health status and vigor of agricultural crops nationally. <br>
**Paper:** [https://doi.org/10.1016/j.rse.2020.112048](https://doi.org/10.1016/j.rse.2020.112048)
**Code:** [Github](https://github.com/kvshashank/Shashank_Codes/tree/master/CONUS_crop_mapping)

<hr>

# Data Science for Weather Impacts on Crop Yield <br>

![test image size](assets/images/frontiers_1.jpg){:width="45%"}
![test image size](assets/images/frontiers_2.jpg){:width="50%"}

**Authors:** Venkata Shashank Konduri, [Thomas Vandal](https://scholar.google.com/citations?user=8cLfchMAAAAJ&hl=en), [Sangram Ganguly](https://www.nasa.gov/centers/ames/earthscience/members/biosphericsciencebranch/Sangram_Ganguly) and [Auroop Ganguly](https://coe.northeastern.edu/people/ganguly-auroop/) <br>
**Journal: Frontiers in Sustainable Food Systems** <br>
**Abstract:** Private businesses in sectors, such as food, energy, and retail, as well as public sector and federal agencies are interested in the predictive understanding of weather impacts on crop yield, which is an important aspect of food security. Scientific literature has mainly examined how crop yield is impacted by growing season-averaged weather indices. Although a few studies did consider weather extremes in their analysis, their scope was either restricted to measuring their conditional relationship with yield or the extreme event types considered were limited. Selection of regression models, whether the more commonly used linear approaches or nonlinear methods, have not been appropriately justified in this context. Here, we develop data-driven methods to examine two inter-related hypotheses for improved scientific understanding and enhanced predictive modeling. The first hypothesis, that extreme weather indices have a statistically significant information content in them is found to be valid based on linear and nonlinear methods for pairwise dependence. The second hypothesis, examines the value addition of nonlinear regression methods, and suggests that linear approaches may not alone be adequate. The results of this study can inform scientific understanding, generation and relevance of indices and end-to-end risk assessment systems in the context of climate impacts on crop yield. An immediate application may be in the context of NASA Earth Exchange (NEX) which facilitates the generation and dissemination of impacts relevant weather data and indices using a multitude of satellite-derived data sets and model outputs. <br>
**Paper:** [https://www.frontiersin.org/articles/10.3389/fsufs.2020.00052/full](https://www.frontiersin.org/articles/10.3389/fsufs.2020.00052/full) <br>
**Code:** [Github](https://github.com/kvshashank/Shashank_Codes/tree/master/crop_yield_modeling)
