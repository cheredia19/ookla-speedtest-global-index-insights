---
title: Ookla Speedtest Global Index insights
description: Insights from the Ookla Speedtest Global Index
---

In today’s fast-paced, digitally connected world, a reliable and fast internet connection is no longer a luxury but a necessity. 

From remote work and online learning to streaming entertainment and staying in touch with loved ones, the internet plays a central role in almost every aspect of daily life. 

The **Ookla Speedtest Global Index** is a valuable tool for understanding global internet performance, offering insights into which countries are leading in broadband and mobile internet speeds. 

This data highlights the importance of infrastructure investment and provides a benchmark for individuals and businesses seeking faster, more reliable connectivity. 

Whether improving productivity, enhancing entertainment experiences, or ensuring seamless communication, having access to high-speed internet is crucial for navigating the demands of modern life. The [Ookla index](https://www.speedtest.net/global-index) helps track global progress, informing users and enabling better decisions for optimizing digital experiences.

## Fixed broadband

<FlatUiTable
  data={{
    url: 'sgi_fb_aug_2024_upd.csv'
  }}
 />

<PlotlyBarChart
  data={{
    url: 'sgi_fb_aug_2024_upd.csv'
  }}
  title="Median speeds by country"
  xAxis="country"
  yAxis="mbps"
/>

<PlotlyBarChart
  data={{
    url: 'fb_ranks.csv'
  }}
  title="Number of countries by median speeds"
  xAxis="speed"
  yAxis="countries"
/>

<PlotlyBarChart
  data={{
    url: 'fb_area_max_mbps.csv'
  }}
  title="Maximum speed by major area"
  xAxis="major_area"
  yAxis="max_mbps"
/> 

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
