---
title: Ookla Speedtest Global Index insights
description: Insights from the Ookla Speedtest Global Index
---

In today’s fast-paced, digitally connected world, a reliable and fast internet connection is no longer a luxury but a necessity. 

From remote work and online learning to streaming entertainment and staying in touch with loved ones, the internet plays a central role in almost every aspect of daily life. 

The **Ookla Speedtest Global Index** is a valuable tool for understanding global internet performance, offering insights into which countries are leading in broadband and mobile internet speeds. 

This data highlights the importance of infrastructure investment and provides a benchmark for individuals and businesses seeking faster, more reliable connectivity. 

Whether improving productivity, enhancing entertainment experiences, or ensuring seamless communication, having access to high-speed internet is crucial for navigating the demands of modern life. The [Ookla index](https://www.speedtest.net/global-index) helps track global progress, informing users and enabling better decisions for optimizing digital experiences.

At DataHub, we have taken the latest available data (August 2024) on **fixed broadband** and **mobile** average speeds by country and “regionalized” the numbers based on the United Nations definition of regions ([1](https://population.un.org/wpp/DefinitionOfRegions/), [2](https://esa.un.org/MigFlows/Definition%20of%20regions.pdf)) to obtain information by areas and regions into those areas.

## Fixed broadband: United Arab Emirates and Singapore set the tone

Three Asian territories recorded the **highest median speed average in fixed broadband connections**, measured in megabits per second (Mbps). The **United Arab Emirates** (297.62), **Singapore** (297.57), and [Hong Kong (special administrative region of China)](https://www.britannica.com/story/is-hong-kong-a-country) (280) are the first three out of 161. 

Chile, the United States of America, Thailand, France, Denmark, Iceland, and Israel completed the top ten.

Below is the full list of median fixed broadband speeds by country:

<FlatUiTable
  data={{
    url: 'sgi_fb_aug_2024_upd.csv'
  }}
 />

The bar chart below shows the countries ordered by speed:

<PlotlyBarChart
  data={{
    url: 'sgi_fb_aug_2024_upd.csv'
  }}
  title="Median speeds by country"
  xAxis="country"
  yAxis="mbps"
/>

Around **17.4% of the countries registered a fixed broadband speed less than 20 Mbps**, while **seven out of 10 (70.8%) averaged an internet speed below 100 Mbps**.

**Thirty-four nations (21.1%) recorded speeds between 100 and 200 Mbps**, mostly in Europe, Asia, Latin America and the Caribbean.

<PlotlyBarChart
  data={{
    url: 'fb_ranks.csv'
  }}
  title="Number of countries by median speeds"
  xAxis="speed"
  yAxis="countries"
/>

The countries from the following major areas averaged the highest internet speed:

- Africa: **Egypt** (76.48 Mbps).
- Asia: **United Arab Emirates** (297.62 Mbps).
- Europe: **France** (223.72 Mbps).
- Latin America and the Caribbean: **Chile** (265.62 Mbps).
- Northern America: **United States** (242.27 Mbps).
- Oceania: **New Zealand** (178.8 Mbps).

<PlotlyBarChart
  data={{
    url: 'fb_area_max_mbps.csv'
  }}
  title="Maximum speed by major area"
  xAxis="major_area"
  yAxis="max_mbps"
/> 

In contrast, these are the nations per major area with the lowest internet speed:

- Africa: **Botswana** (8.53 Mbps).
- Asia: **Turkmenistan** (3.63 Mbps).
- Europe: **Bosnia and Herzegovina** (30.74 Mbps).
- Latin America and the Caribbean: **Suriname** (12.09 Mbps).
- Northern America: **Canada** (188.2 Mbps).
- Oceania: **Fiji** (26.36 Mbps).

<PlotlyBarChart
  data={{
    url: 'fb_area_min_mbps.csv'
  }}
  title="Minimum speed by major area"
  xAxis="major_area"
  yAxis="min_mbps"
/>

<PlotlyBarChart
  data={{
    url: 'fb_region_max_mbps.csv'
  }}
  title="Maximum speed by region"
  xAxis="region"
  yAxis="max_mbps"
/> 

<PlotlyBarChart
  data={{
    url: 'fb_region_min_mbps.csv'
  }}
  title="Minimum speed by region"
  xAxis="region"
  yAxis="min_mbps"
/> 

## Mobile

<FlatUiTable
  data={{
    url: 'sgi_mob_aug_2024.csv'
  }}
 />

<PlotlyBarChart
  data={{
    url: 'sgi_mob_aug_2024.csv'
  }}
  title="Median speeds by country"
  xAxis="country"
  yAxis="mbps"
/> 
 
<PlotlyBarChart
  data={{
    url: 'mob_ranks.csv'
  }}
  title="Number of countries by median speeds"
  xAxis="speed"
  yAxis="countries"
/> 

<PlotlyBarChart
  data={{
    url: 'mob_area_max_mbps.csv'
  }}
  title="Maximum speed by major area"
  xAxis="major_area"
  yAxis="max_mbps"
/> 

<PlotlyBarChart
  data={{
    url: 'mob_area_min_mbps.csv'
  }}
  title="Minimum speed by major area"
  xAxis="major_area"
  yAxis="min_mbps"
/>

<PlotlyBarChart
  data={{
    url: 'mob_region_max_mbps.csv'
  }}
  title="Maximum speed by region"
  xAxis="region"
  yAxis="max_mbps"
/> 

<PlotlyBarChart
  data={{
    url: 'mob_region_min_mbps.csv'
  }}
  title="Minimum speed by region"
  xAxis="region"
  yAxis="min_mbps"
/> 

## Fastest speed

<FlatUiTable
  data={{
    url: 'sgi_fb_mob_fastest.csv'
  }}
 /> 
