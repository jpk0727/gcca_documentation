---
description: A brief overview of the project and contents of this documentation.
---

# Overview

{% file src=".gitbook/assets/gcca\_final-report.pdf" caption="Download the Report" %}

## Introduction

These instructions are a supplement to a report written by a team of Master of Science in Sustainability Management students working as a Capstone consultancy at Columbia University. The project was undertaken at the request of the Global Cool Cities Alliance \(GCCA\), a non-profit organization focused on accelerating a global transition to cooler, healthier cities through increasing the solar reflectance of urban surfaces. Cities are hotter than their surrounding areas as vegetation is replaced with buildings, roadways, and other structures to accommodate growing populations - a phenomenon called the Urban Heat Island \(UHI\) effect. As pavement makes up 30% of a city’s surface on average, implementing cool roadway solutions will play an important role in improving a city’s heat resilience. In early 2020, GCCA launched the “Cool Roadways Partnership”, an initiative with manufacturers, public works officials, and sustainability directors across the U.S. to initiate cool roadway pilot projects to mitigate the UHI effect. The Capstone team was tasked with developing a prioritization tool based on equity and community health that GCCA and its Cool Roadway Partner cities will use to identify cool roadway pilot locations across the country.

The following guide is intended for city representatives that are looking to ease the implementation of a cool roadway solution. First, the instructions will help you to score census tracts within your city based on heat vulnerability and UHI severity in order to site where cool pavement coating projects can be installed for maximum benefit. Second, the instructions will guide you through a cost-benefit analysis methodology to help you measure the impacts of implementing a cool pavement solution.

In order to get started there are two types of data that will be needed, 1\) social data that helps to score heat vulnerability and 2\) physical data that provides insight into the severity of a region's urban heat island. The following instructions will walk you through creating this index by:

1. **Acquiring the data.**
2. **Importing the data into a preconfigured Excel sheet.**
3. **Processing satellite data in GIS.**
4. **Merging the physical and social parameters into one overall score.** 
5. **Creating a choropleth map to visualize the final results** 

{% hint style="warning" %}
Requirements

* **Install or have** [**QGIS**](https://qgis.org/en/site/forusers/download.html) **downloaded on your computer.**
* **Install or have Microsoft Excel downloaded on your computer.**
* **Create or have an** [**Earth Explorer Account**](https://earthexplorer.usgs.gov/)**.**
* **Install or have** [**USGS Bulk Download Application**](https://dds.cr.usgs.gov/bulk) **\(BDA\)**
  * \*\*\*\*[**Java Runtime Environment**](https://www.java.com/en/download/manual.jsp) **is a pre-requisite for BDA.**
{% endhint %}

