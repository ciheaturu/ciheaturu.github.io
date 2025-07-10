---
layout: page
title: UAV-Based Forest Disturbance Assessment
description: Integrating LiDAR and multispectral data to assess forest status and map disturbance severity in West African forests
img: assets/img/3.jpg
importance: 1
category: research
giscus_comments: true
---

This research demonstrates the innovative integration of UAV LiDAR and multispectral technologies for comprehensive forest ecosystem assessment in West Africa. Our methodology combines structural and spectral data to create a powerful tool for monitoring forest health and disturbance severity. The study introduces an Integrated Disturbance Index (IDI) that fuses canopy structural metrics from LiDAR data with spectral vitality indicators from multispectral vegetation indices. This approach enables precise classification of forest disturbance levels across tropical forest patches.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="Study area and design" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
  <strong>Fig. 1.</strong> Study area and study design. Upper left - The location of Benin Republic in West Africa (in red); bottom left - Map of Benin Republic showing the location of EARF (red dot); Upper right - UAV multispectral and LiDAR setup over the field site, EARF; bottom right - Google Earth Image of EARF showing the 20 forest inventory plot locations.
</div>

## Methodology Framework

Our research methodology centers on the development of an Integrated Disturbance Index that leverages the complementary strengths of both LiDAR and multispectral sensors. The framework processes structural properties from LiDAR data alongside spectral characteristics from vegetation indices through principal component analysis (PCA).

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/2.jpg" title="IDI framework" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
  <strong>Fig. 2.</strong> Integrated Disturbance Index (IDI) framework for mapping forest disturbance. The framework integrates canopy structural metrics derived from LiDAR data and spectral vitality indicators captured by vegetation indices.
</div>

The IDI successfully delineates three distinct forest disturbance levels:  
- **Low disturbance** (> 0.65)  
- **Medium disturbance** (0.35–0.65)  
- **High disturbance** (< 0.35)  

This classification system enables targeted conservation strategies and resource allocation based on specific disturbance severity levels.

## Spectral Analysis Results

The multispectral analysis revealed comprehensive vegetation stress patterns across the 560-hectare Ewe-Adakplame relict forest. Our vegetation indices captured varying degrees of forest health, from robust canopy areas to severely stressed vegetation zones.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="Vegetation indices spatial distribution" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
  <strong>Fig. 3.</strong> Spatial distribution of VIs derived from the UAV multispectral data, including (a) GNDVI, (b) EVI, (c) SAVI, (d) NDRE, and (e) LCI. Areas of healthy vegetation are represented by dark green hues. In contrast, regions of stressed vegetation exhibit a gradient that transitions from light green to yellow and ultimately to red, reflecting varying degrees of vegetative stress.
</div>

The spectral analysis demonstrates clear spatial patterns of vegetation health across the forest patch. Dark green areas indicate healthy vegetation with high photosynthetic activity, while the gradient from light green to yellow and red reveals progressive vegetation stress levels.

## Performance Validation and Accuracy Assessment

Our comprehensive validation approach compared the performance of different data integration strategies. The results demonstrate the superior accuracy of the integrated approach over single-sensor methodologies.

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="Performance comparison" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="Accuracy metrics" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
  <strong>Fig. 4.</strong> Confusion matrices and performance metrics for disturbance severity classification with the different datasets: (a) IDI, (b) LiDAR CHM, (c) Spectral VIs.
</div>

The validation results show that our IDI achieved **95% overall accuracy** in disturbance detection, significantly outperforming both LiDAR-only (**80%**) and multispectral-only (**75%**) approaches. This superior performance underscores the value of data integration for forest assessment applications.

## Key Findings and Conservation Implications

The analysis of the Ewe-Adakplame relict forest revealed concerning disturbance patterns that highlight the urgent need for conservation intervention.  
- **23%** of the forest area has experienced **low disturbance**,  
- **28%** is under **medium disturbance**, and  
- **49%** shows **high disturbance**.

These results demonstrate that more than three-quarters of this relict forest exhibits medium to high levels of disturbance, emphasizing the critical need for tailored conservation strategies. The spatial distribution of disturbance levels provides valuable insights for prioritizing conservation efforts and developing site-specific management plans.

## Technical Implementation

The integration methodology employs advanced geospatial analysis techniques to combine complementary sensor data. The **LiDAR data** provides detailed canopy height models and structural metrics, while the **multispectral imagery** captures spectral signatures related to vegetation health and stress. **Principal component analysis (PCA)** serves as the fusion mechanism, effectively combining these diverse data sources into a unified disturbance assessment framework.

This approach maximizes the information content from both sensor types while minimizing redundancy. The methodology's robustness and transferability make it suitable for application across diverse tropical forest patches, providing forest managers and conservationists with an effective tool for monitoring forest health and assessing disturbance severity.

## Future Applications and Scalability

This research establishes a foundation for **operational forest monitoring systems** that can support **data-driven decision-making** in forest conservation and sustainable management. The methodology's **scalability** enables its application across **larger forest landscapes** and different ecological contexts.

The integration framework developed here has **potential for real-time forest monitoring applications**, enabling **rapid response** to emerging disturbance events and supporting **adaptive management strategies**. Future developments could incorporate **additional sensor types** (e.g., hyperspectral, thermal, SAR) and **machine learning algorithms** to further enhance forest disturbance assessment capabilities and support forest restoration goals.
