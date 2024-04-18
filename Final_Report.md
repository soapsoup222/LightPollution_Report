---
title: "Light Pollution in Zeeland Report"
author: "Vayona Narekuli"
date: "April 18, 2024"
output: html_document
---

# Light Pollution in Zeeland

## To what extent have protected "duisternisgebieden" (darkness areas) appointed in January 2019 limited light pollution in Zeeland?

Vayona Narekuli

UCR Data Center

Apprenticeship Spring 2024

## Introduction

The implementation of the Darkness Areas Act in Middelburg in 2019 marked a significant step in addressing the issue of light pollution in Zeeland. This legislation, aimed at designating specific areas for darkness preservation(reference to the areas), underscored a growing recognition of the adverse effects of excessive artificial illumination on both the environment and human health. However, despite its noble intentions, the effectiveness of this act in reducing light pollution remains a subject of inquiry.

Understanding and quantifying light pollution presents formidable challenges. Light and luminosity can be detected through various means, ranging from satellite observations to ground-level measurements. Factors such as the spectrum of visible light captured and the methodologies employed can significantly influence the assessment of light pollution levels. Hence, ascertaining the true impact of the Darkness Areas Act necessitates a nuanced approach that considers these complexities.

This investigation focuses on assessing the effectiveness of the 2019 Darkness Areas Law in reducing light pollution in Zeeland. Using NASA VIIRS satellite data, the research aims to offer practical insights into the impact of the legislation. However, it's important to recognize the possible influence of external factors, such as the COVID-19 pandemic, which coincided with the law's implementation. This study seeks to understand the impact of the Darkness Areas Act amidst the societal changes caused by the pandemic. By considering factors like shifts in population and economic activities, the research aims to provide reliable insights into the battle against light pollution in Zeeland, ensuring the integrity of its findings.

## Data

This study relied on NASA VIIRS data, known as Black Marble Night Time Lights data, for evaluating light pollution in Zeeland. This data uses remote sensing techniques to detect artificial light in units of radiance, and calibrates for confounding variables such as moonlight. There are many alternative approaches to researching light pollution, One such approach involves deploying ground-based measuring devices strategically. Although this approach may necessitate specialized equipment and expertise, it provides a unique perspective on light pollution dynamics and can help validate findings derived from satellite observations. This study however will focus on Black Marble data in order to maintain consistency across years. Additionally, both raw and calibrated Black Marble data is updated daily, making it possible for the methods in this project to be used for future analysis.

However, it's essential to acknowledge VIIRS's limitations. Primarily designed to detect light sources near nadir, the dataset may not fully capture the extent of LED lighting, which often emits light at angles away from the vertical. Consequently, there's a possibility that VIIRS underestimates the true level of light pollution in areas where LED lighting is prevalent. However, as the main goal of this report is to identify changes in light pollution across years,

This research will mostly focus on yearly composite observations of luminosity.

[Descriptive Statistics/Visualizations of the data]

```{r message=FALSE, warning=FALSE,}
#Using the package made as a part of this project in order to work with Black Marble data
install_github("soapsoup222/lightpollutionNL")
library(lightpollutionNL)



```

## Methods

## Analysis

## Conclusion
