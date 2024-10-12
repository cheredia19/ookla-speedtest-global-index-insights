---
title: Ookla Speedtest Global Index insights
description: Insights from the Ookla Speedtest Global Index
---

<FlatUiTable
  data={{
    url: 'sgi_fb_aug_24.csv'
  }}
 />

 Looks kinda cool. What about a linechart? Let's see what this would look like:
 <LineChart 
  data={{ url: 'data.csv' }} 
  title="C02 PPM per decade" 
  xAxis="year"
  yAxis="value"
  color="key"
/>

 <LineChart 
  data={{ url: 'data.csv' }} 
  title="C02 PPM per decade" 
  xAxis="year"
  yAxis="co2"
  color="key"
/>

<LineChart
  data={{
    values: [
      { date: '2019-01-01', foo: 10, bar: 10, key: 30 },
      { date: '2020-01-02', foo: 30, bar: 20, key: 20 },
      { date: '2021-01-03', foo: 40, bar: 20, key: 10 },
      { date: '2022-01-04', foo: 1, bar: 60, key: 20 }
    ]
  }}
  title="CO2 PPM per Decade"
  xAxis="date"
  color="key"
/>

<LineChart
  data={{
    values: [
      { date: '2019-01-01', foo: 10, bar: 10, key: 30 },
      { date: '2020-01-02', foo: 30, bar: 20, key: 20 },
      { date: '2021-01-03', foo: 40, bar: 20, key: 10 },
      { date: '2022-01-04', foo: 1, bar: 60, key: 20 }
    ]
  }}
  title="CO2 PPM per Decade"
  xAxis="foo"
  color="key"
/>

<LineChart
  data={{
    values: [
      { date: '2019-01-01', foo: 10, bar: 10, key: 30 },
      { date: '2020-01-02', foo: 30, bar: 20, key: 20 },
      { date: '2021-01-03', foo: 40, bar: 20, key: 10 },
      { date: '2022-01-04', foo: 1, bar: 60, key: 20 }
    ]
  }}
  title="CO2 PPM per Decade"
  xAxis="foo"
  yAxis="value"
  color="Values"
/>

If you want to explore more of what's possible:

<div class="middle-button-container">
    <a href="https://datahub.io/docs" class="middle-button">Go to the docs</a>
</div>
