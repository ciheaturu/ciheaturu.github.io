---
layout: page
title: An object-based sampling approach for validating fragmented forest cover in tropical landscapes
description: Developing robust validation methods for forest cover maps in complex tropical ecosystems
img: assets/img/forest_validation.jpg
importance: 1
category: work
---

Validating forest cover maps is essential for evidence-based conservation and sustaining ecosystem services. However, complex spatial patterns in fragmented tropical forest landscapes—often comprising non-contiguous forest patches, interspersed with agricultural lands and other land cover types—pose considerable difficulties for accuracy assessment using conventional techniques.

This project developed an integrated object-based sampling (IOBS) method that combines stratified random sampling, proportional allocation, and sample distance optimization to address these challenges. The IOBS method was applied to assess the accuracy of the Japan Aerospace Exploration Agency (JAXA) global 25 m PALSAR-2/PALSAR forest/non-forest (FNF) 2020 map across 14 ecoregions in Nigeria.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/workflow_diagram.jpg" title="IOBS Workflow" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/optimization_process.jpg" title="Distance Optimization" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/regression_analysis.jpg" title="Accuracy Analysis" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <strong>Fig. 1.</strong> Workflow. The JAXA-FNF 2020 dataset represents the 25 m forest/non-forest product validated in this study. <strong>Fig. 2.</strong> An illustration of the distance optimization process using Lloyd's Algorithm. <strong>Fig. 3.</strong> Linear regression graphs illustrating the relationship between accuracy metrics and predictor variables (sample size and forest density). (A) Linear regression graphs of accuracy metrics (OA, PA, UA) versus sample size, with coefficients of determination (R²) of 0.30, 0.34, and 0.41, respectively. (B) Linear regression graphs of accuracy metrics (OA, PA, UA) versus forest density, with R² values of 0.14, 0.85, and 0.43, respectively. R² quantifies the proportion of variance in the accuracy metric explained by the predictor variable.
</div>

## Key Findings

The IOBS method demonstrated substantially higher spatial variability (CV = 109.37) and heterogeneity (HI = 0.21) compared to conventional methods including simple random, systematic, and stratified random sampling (CV = 28.84–53.93, HI = 0.05–0.11). 

The IOBS estimated an accuracy of **81.1%**, closely aligning with the true accuracy of 82.4% and significantly outperforming other methods (75.3%–79.7%). This higher performance stems from the method's ability to capture a broad range of forest conditions—from extensive contiguous cover to small, fragmented patches—while minimizing spatial autocorrelation through distance optimization.

## Methodological Innovation

The integrated approach combines three key components:

1. **Stratified Random Sampling**: Ensures representative coverage across different forest density classes
2. **Proportional Allocation**: Maintains appropriate sample distribution relative to stratum size
3. **Distance Optimization**: Uses Lloyd's Algorithm to minimize spatial autocorrelation and maximize spatial coverage

## Implications

By better representing local heterogeneity, IOBS offers a robust and precise framework for validating categorical forest cover maps in complex tropical landscapes. This advancement in accuracy assessment practices has significant implications for remote sensing applications in tropical forest monitoring, conservation planning, and ecosystem service assessment.

The method is particularly valuable for fragmented landscapes where traditional sampling approaches may miss critical forest patches or overrepresent certain forest conditions, leading to biased accuracy estimates that can compromise conservation decision-making.
