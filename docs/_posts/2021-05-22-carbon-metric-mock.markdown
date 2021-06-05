---
layout: post
title:  "Carbon Metric Mock"
date:   2021-05-22 03:18:40 +0200
---

I mocked out a carbon-emission wiget for display in space-operations control rooms.

![carbon-capture-metric]({{ site.url }}/assets/img/CO2-metric-mock.png)

I tried to outline this idea [in a previous post]({{ site.url }}/2021/05/20/paleo-software-in-space-ops.html).

The main idea is that using some back-of-an-envelope maths,
we can get a rough **lower limit** to the carbon emitting every second from system operations.

In the example above I estimated the power consumption for a web application (website) with a small number of users.
Along with the number itself, the metric shows the local *trend* of the value:
 * is it up or is it down (over a recent timeframe)?
 * is that good or is it bad?

The actual implementation would only be marginally more complicated.

Only roughly estimated values are needed to give a sense of *scale* to the climate cost  of ongoing operations.

For space operations this cost might include a large initial release of greenhouse gas at launch,
followed by a prolonged but less intense period of carbon emission during orbit.

A companion metric would also be a helpful to display cumulative carbon emissions over the entire period of operation, as a time-series plot.
