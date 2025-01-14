---
title: Landsat 4-5 TM Normalized Difference Water Index - NDWI
parent: Landsat 4-5 TM
grand_parent: Landsat
layout: script
permalink: /landsat-4-5-tm/ndwi/
nav_exclude: true
---


## Evaluate and Visualize

- [EO Browser](https://sentinelshare.page.link/2AW7)
 
## General description of the script
The NDWI is used to monitor changes related to water content in water bodies. As water bodies strongly absorb light in visible to infrared electromagnetic spectrum, NDWI uses green and near infrared bands to highlight water bodies. It is sensitive to built-up land and can result in over-estimation of water bodies. 

**NDWI = (GREEN - NIR) / (GREEN + NIR)**

For Landsat 7 ETM+, the index calculates as: 

**NDWI = (B03 - B05) / (B03 + B05)**

Values description: Index values greater than 0.5 usually correspond to water bodies. Vegetation usually corresponds to much smaller values and built-up areas to values between zero and 0.2.

See also [this page](https://custom-scripts.sentinel-hub.com/sentinel-2/ndwi/#).

## Description of representative images

The NDWI over Rome. Acquired on 2020-07-30.
![The script example 1](fig/fig1.png)

