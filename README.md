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

By UN regions, these are the countries with the highest fixed broadband internet speed to date:

- Australia and New Zealand: **New Zealand** (178.80 Mbps).
- Caribbean: **Trinidad and Tobago** (119.78 Mbps).
- Central America: **Panama** (151.94 Mbps).
- Central Asia: **Uzbekistan** (69.37 Mbps).
- Eastern Africa: **Mauritius** (51.61 Mbps).
- Eastern Asia: **Hong Kong (SAR)** (280.00 Mbps).
- Eastern Europe: ** Romania** (200.94 Mbps).
- Melanesia: **Fiji** (26.36 Mbps).
- Middle Africa: **Gabon** (41.42 Mbps).
- Northern Africa: **Egypt** (76.48 Mbps).
- Northern America: **United States** (242.27 Mbps).
- Northern Europe: **Denmark** (219.23 Mbps).
- South America: **Chile** (265.62 Mbps).
- South-Eastern Asia: **Singapore** (297.57 Mbps).
- Southern Africa: **South Africa** (47.35 Mbps).
- Southern Asia: **Nepal** (71.62 Mbps).
- Southern Europe: **Spain** (205.17 Mbps).
- Western Africa: **Côte d'Ivoire** (62.04 Mbps).
- Western Asia: **United Arab Emirates** (297.62 Mbps).
- Western Europe: **France** (223.72 Mbps).

<PlotlyBarChart
  data={{
    url: 'fb_region_max_mbps.csv'
  }}
  title="Maximum speed by region"
  xAxis="region"
  yAxis="max_mbps"
/>

And the States that registered the lowest fixed broadband speed by region were:

- Australia and New Zealand: **Australia** (71.87 Mbps).
- Caribbean: **Dominican Republic** (36.1 Mbps).
- Central America: **Belize** (44.74 Mbps).
- Central Asia: **Turkmenistan** (3.53 Mbps).
- Eastern Africa: **Ethiopia** (9.48 Mbps).
- Eastern Asia: **Mongolia** (71.45 Mbps).
- Eastern Europe: **Belarus** (61.05 Mbps).
- Melanesia: **Fiji** (26.36 Mbps).
- Middle Africa: **Cameroon** (9.94 Mbps).
- Northern Africa: **Tunisia** (10.58 Mbps).
- Northern America: **Canada** (188.2 Mbps).
- Northern Europe: **Estonia** (80.14 Mbps).
- South America: **Suriname** (12.09 Mbps).
- South-Eastern Asia: **Myanmar (Burma)** (21.56 Mbps).
- Southern Africa: **Botswana** (8.53 Mbps).
- Southern Asia: **Afghanistan** (3.63 Mbps).
- Southern Europe: **Bosnia and Herzegovina** (30.74 Mbps).
- Western Africa: **Liberia** (8.9 Mbps).
- Western Asia: **Syria** (3.65 Mbps).
- Western Europe: **Germany** (90.63 Mbps).
   
<PlotlyBarChart
  data={{
    url: 'fb_region_min_mbps.csv'
  }}
  title="Minimum speed by region"
  xAxis="region"
  yAxis="min_mbps"
/> 

## Mobile: two countries over 300 megabits per second

**The United Arab Emirates** also has the fastest mobile connection with a staggering speed of 398.51 Mbps, according to the Ookla Speedtest Global Index. **The UAB mobile internet is even greater than their fixed broadband**. 

**Qatar** (344.34) is second on the 111-territories list, and **Kuwait** (239.83 Mbps) is third-ranked. 

The three Western-Asian outlets are **the only ones with a mobile speed of over 200 Mbps**.

Two other Asian countries (**South Korea** and **Saudi Arabia**) and five European nations (**Netherlands**, **Denmark**, **Norway**, **Bulgaria**, and **Luxembourg**) make the top ten.

**Singapore** is in eleventh place. Despite having a fixed broadband internet speed of 297.57 Mbps, the [city-state](https://www.britannica.com/place/Singapore) mobile performance is *just* 114.3 Mbps.

The complete list is below:

<FlatUiTable
  data={{
    url: 'sgi_mob_aug_2024.csv'
  }}
 />

The following chart shows the nations ordered by mobile speed: 

<PlotlyBarChart
  data={{
    url: 'sgi_mob_aug_2024.csv'
  }}
  title="Median speeds by country"
  xAxis="country"
  yAxis="mbps"
/> 

Three out of 10 countries (30.6%) **are located in the 20-40 Mbps range** when it comes to mobile speed. Among them are **Guatemala**, **Iran**, **Lebanon**, **Argentina**, **Mexico**, **Indonesia**, **Egypt**, **Russia**, **Nigeria**, and **Ukraine**, to cite a few.

Almost two-thirds (64%) of the territories listed **record a speed under 60 Mbps**, according to the Global Index. A sign that maybe the mobile internet is not as developed as the fixed broadband in most countries.
 
<PlotlyBarChart
  data={{
    url: 'mob_ranks.csv'
  }}
  title="Number of countries by median speeds"
  xAxis="speed"
  yAxis="countries"
/>

Grouped by the UN's major areas, the countries with the fastest mobile internet are:

- Africa: **South Africa** (51,96 Mbps).
- Asia: **United Arab Emirates** (398,51 Mbps).
- Europe: **Netherlands** (133,44 Mbps).
- Latin America and the Caribbean: **Brazil** (73,08 Mbps).
- Northern America: **United States** (103,73 Mbps).
- Oceania: **Australia** (97,86 Mbps).

<PlotlyBarChart
  data={{
    url: 'mob_area_max_mbps.csv'
  }}
  title="Maximum speed by major area"
  xAxis="major_area"
  yAxis="max_mbps"
/> 

The countries with the slowest mobile internet by geographical area are:

- Africa: **Libya** (15,1 Mbps).
- Asia: **Yemen** (7,91 Mbps).
- Europe: **Belarus** (11,98 Mbps).
- Latin America and the Caribbean: **Bolivia** (11,26 Mbps).
- Northern America: **Canada** (74,87 Mbps).
- Oceania: **New Zealand** (78,46 Mbps).

<PlotlyBarChart
  data={{
    url: 'mob_area_min_mbps.csv'
  }}
  title="Minimum speed by major area"
  xAxis="major_area"
  yAxis="min_mbps"
/>

As seen above, mobile speed in the areas is similar, except in North America and Oceania, where it's faster.

These countries hold the fastest mobile internet in their regions:

- Australia and New Zealand: **Australia** (97,86 Mbps).
- Caribbean: **Dominican Republic** (32,99 Mbps).
- Central America: **Guatemala** (39,73 Mbps).
- Central Asia: **Kazakhstan** (51,25 Mbps).
- Eastern Africa: **Kenya** (29,49 Mbps).
- Eastern Asia: **South Korea** (141,23 Mbps).
- Eastern Europe: **Bulgaria** (117,64 Mbps).
- Northern Africa: **Morocco** (40,89 Mbps).
- Northern America: **United States** (103,73 Mbps).
- Northern Europe: **Denmark** (130,05 Mbps).
- South America: **Brazil** (73,08 Mbps).
- South-Eastern Asia: **Singapore** (114,30 Mbps).
- Southern Africa: **South Africa** (51,96 Mbps).
- Southern Asia: **India** (96,38 Mbps).
- Southern Europe: **North Macedonia** (94,33 Mbps).
- Western Africa: **Nigeria** (20,19 Mbps).
- Western Asia: **United Arab Emirates** (398,51 Mbps).
- Western Europe: **Netherlands** (133,44 Mbps).

<PlotlyBarChart
  data={{
    url: 'mob_region_max_mbps.csv'
  }}
  title="Maximum speed by region"
  xAxis="region"
  yAxis="max_mbps"
/>

And these States have the slowest mobile speed in their regions:

- Australia and New Zealand: **New Zealand** (78,46 Mbps).
- Caribbean: **Dominican Republic** (32,99 Mbps).
- Central America: **Nicaragua** (21,49 Mbps).
- Central Asia: **Uzbekistan** (36,19 Mbps).
- Eastern Africa: **Tanzania** (22,85 Mbps).
- Eastern Asia: **Japan** (47,43 Mbps).
- Eastern Europe: **Belarus** (11,98 Mbps).
- Northern Africa: **Libya** (15,1 Mbps).
- Northern America: **Canada** (74,87 Mbps).
- Northern Europe: **Ireland** (41,12 Mbps).
- South America: **Bolivia** (11,26 Mbps).
- South-Eastern Asia: **Cambodia** (28,7 Mbps).
- Southern Africa: **Namibia** (27,94 Mbps).
- Southern Asia: **Afghanistan** (8,48 Mbps).
- Southern Europe: **Bosnia and Herzegovina** (20,56 Mbps).
- Western Africa: **Nigeria** (20,19 Mbps).
- Western Asia: **Yemen** (7,91 Mbps).
- Western Europe: **Germany** (56,69 Mbps).

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
