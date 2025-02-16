---
icon: magnifying-glass-chart
---

# Measurement, Reporting & Verification

We monitor the farms using remote sensing technologies (drones and satellite photos), and through satellite monitoring combined with climatic data, we will analyze the health of vegetation and crops. For satellite monitoring, we will implement images from [Landsat 8](https://www.usgs.gov/landsat-missions/landsat-8) and [Sentinel](https://sentinels.copernicus.eu/web/sentinel/home) satellites combined with advanced analysis tools.

Also, through the use of drones, we will fulfill multiple functions, such as mapping different areas, analyzing vegetation indices, and monitoring crops, and diseases. This will result in a reduction in production costs, increased efficiency and productivity, time savings, and better management decisions.

### On The Ground Sensing

|                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Measurement Type**         | **Methodology**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Soil Mosture Probes          | <ul><li><strong>Volumetric Water Content</strong>: Determines the amount of water present in the soil in relation to its total volume, providing an accurate measurement of moisture levels in the various soil layers. </li><li><strong>Electrical Conductivity</strong>: Measures the soil’s ability to conduct electricity, which is an important indicator for assessing soil salinity and nutrient availability. </li><li><strong>Soil Temperature</strong>: Records the soil temperature, a crucial factor that influences the biological and chemical processes affecting plant growth and development.</li></ul> |
| Community-based Analytics    | <ul><li>Crop Cycle </li><li>Plant Analysis </li><li>Water Analysis </li><li>Soil Texture </li><li>Diseases</li></ul>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Technologies & Digital Tools | <ul><li><a href="https://www.silvi.earth/">Silvi</a> for Individual Plants GPS &#x26; Health Tracking </li><li><a href="https://apps.apple.com/in/app/impact-miner/id6448894610">Atlantis App</a> for Data Collection, Project Management &#x26; 3rd Party Attestations</li><li>QGIS for analyzing vegetation indices</li><li><a href="https://www.pix4d.com/product/pix4dcapture">Pix4Dcapture</a> for drone flight planning</li></ul>                                                                                                                                                                                  |

### Remote Sensing

#### Vegetation & Environment Indices

[**NDVI**](https://gisgeography.com/ndvi-normalized-difference-vegetation-index/) **(Normalized Difference Vegetation Index)**

It is the most common vegetation index in remote sensing. We will use it throughout the crop production season, except when vegetation and its canopy are too sparse, as its spectral reflectance is too low.

> ```
> Fórmula: NDVI = (NIR – RED) / (NIR + RED)
> ```

[**ReCl**](https://www.livestocking.net/vegetation-indices-use-in-farming)

The ReCl vegetation index responds to the chlorophyll content in leaves, which is nourished by nitrogen. ReCl reflects the photosynthetic activity of vegetation. We will use it during the active development phase of the vegetation.

> ```
> Fórmula: ReCI = (NIR / RED) – 1
> ```

[**NDRE**](https://naldc.nal.usda.gov/download/4190/PDF)&#x20;

It combines the spectral bands of near-infrared (NIR) and a specific band for the narrow range between visible red and the transition zone (the so-called red-edge region). We will use this index to monitor crops that have reached the maturity phase.

> ```
> Fórmula: NDRE = (NIR – RED EDGE) / (NIR + RED EDGE)
> ```

[**MSAVI**](https://www.usgs.gov/landsat-missions/landsat-modified-soil-adjusted-vegetation-index)

It is designed to mitigate the effects of soil on crop monitoring results. Therefore, we will apply it when NDVI cannot provide accurate values, especially with a high percentage of bare soil, sparse vegetation, or low chlorophyll content in plants. We will implement it at the beginning of the crop production season when seedlings begin to establish.

> ```
> Fórmula: MSAVI = (2 * Band 4 + 1 – sqrt ((2 * Band 4 + 1)2 – 8 * (Band 4 – Band 3))) / 2
> ```

### Annual Reports

1. Environmental Impact: Annual carbon sequestration rates, changes in local biodiversity indices.
2. Economic Impact: GDP contribution, changes in average household income.
3. Social Impact: Changes in community well-being indices, education rates, and health outcomes.
4. Sustainability: Annual sustainability audit measuring progress across all 8 forms of capital.

> This information enables more efficient and sustainable management of irrigation and nutrients, improving both crop yields and the conservation of natural resources.
