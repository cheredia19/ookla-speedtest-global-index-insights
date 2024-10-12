---
title: Ookla Speedtest Global Index insights
description: Insights from the Ookla Speedtest Global Index
---

## Median country speeds (updated August 2024)

### Fixed broadband

<FlatUiTable
  data={{
    url: 'sgi_fb_aug_2024.csv'
  }}
 />

<PlotlyBarChart
  data={{
    url: 'sgi_fb_aug_2024.csv'
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

### Mobile

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

### Fastest speed

<FlatUiTable
  data={{
    url: 'sgi_fb_mob_fastest.csv'
  }}
 /> 
