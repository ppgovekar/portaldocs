﻿# SingleMetric

 
<a name="basics"></a>
### Basics
SingleMetric shows a single value for a metric


<!-- TODO get an IMAGE to embed here -->

<!-- TODO get an SAMPLE CODE to embed here -->

 
<a name="when-to-use"></a>
### When to use
Use SingleMetric to show a single value for a metric.  For example, what is the current CPU utilization of a VM.

The SDK offers a set data visualization controls.  Choose the one that is most suitable to your need.
* **AreaChart** - displays quantitative data like a LineChart with the area between axis and the lines filled with colors.
* **BarChart** - displays categorical data using rectangular bars of proportional length to represent values.
* **Donut** - displays proportional data as part of a whole.
* **LineChart** - displays a series of data points connected by straight line segments.
* **Map** - displays data with longitude and latitude coordinates on a world map.
* **Metrics** - displays a single value for a set of metrics
* **MonitorChartV2** - displays the metrics for your resource and inherently knows how to fetch data for your resource.
* **QuotaGauge** - displays the current value relative to a quota (limit) and total.
* **ScatterChart** - displays a plot of data points without any connecting lines
* **SingleMetric** - displays a single value for a metric
* **SingleValueGauge** - displays the status of a current value relative to an optional total.  



 
<a name="best-practices"></a>
### Best practices


<a name="best-practices-do"></a>
#### Do

* Clearly label the metric

<a name="best-practices-don-t"></a>
#### Don&#39;t

* Don't show a single metric if a few more would help the user understand the situation better.  The Metrics control can display multiple metrics.



 
<a name="developer-tips-and-tricks"></a>
### Developer tips and tricks



<a name="developer-tips-and-tricks-interactive-control-and-sample-source-code"></a>
#### Interactive control and sample source code
Go to the playground site to use the latest control and get source code for your project.  [Learn more about playground](./top-extensions-controls-playground.md).

*  <a href="https://ms.portal.azure.com/?Microsoft_Azure_Playground=true#blade/Microsoft_Azure_Playground/ControlsIndexBlade/SingleMetric_create_Playground" target="_blank">SingleMetric in the interactive controls playground</a>

 


 
<a name="related-info"></a>
### Related info

* Azure design guidance:  http://aka.ms/portalfx/design


