---
layout: post
title:  "Paleo Software Engineering 2"
date:   2021-05-19 08:33:51 +0200
---

Read the first part [here]({{ site.url }}/2021/05/16/decarbonised-software-engineering.html).

## Even winning feels like losing

Lets consider the following scenario:

Following massive popular revolution, hydrocarbon-based capitalism is wiped out overnight.
The EU transitions immediately to a renewable-based energy economy.
What happens to the rest of the economy - and specifically the software underpinning modern life?

The vast majority of existent software is designed with the underlying assumption that our power grid is always-available and high-capacity.
Much of the world's computation occurs in enormous data centres across the globe, dependent upon a constant and reliable power supply.

This infrastructure, handling the bulk of online interaction from your twitter feed to your amazon shopping cart,
is simply unable to function in the post-hydrocarbon economy.

The most popular renewable energy sources (wind & solar) have pretty serious limitations: unreliability & low power density.
In adverse weather conditions they simply don't function,
and far more physical power sources are required compared to fossil-fuel/nuclear power.
These issues may be *mitigated* by having a well-connected grid spanning a large geographical area as well as accurate weather prediction,
to minimise the impact of local conditions upon power output.
However, accurate weather prediction is an early casualty of the climate crisis, and technological solutions to even-out grid usage
are beset by their own problems:
 - massive batteries to store renewable-generated energy are expensive and come with their own hefty carbon price-tag
 - nuclear (fission) power generation has insufficient uptake as well as it's own significant political and technical problems

The world we have constructed around data-as-a-commodity is simply incompatible with our post-hydrocarbon future. This seems like a pretty serious problem; as software engineers, what are we to do?

Two approaches spring to mind, depending how we think of **engineering** as a discipline.

### The technocratic fix

> Engineering is a means of solving business problems to generate profit.

From this position, we seek to maintain our existing economic system - based on limitless growth, just like cancer.

Power for our data centres is expensive or unavailable? Fine, just pass the costs on to the consumer.
Tech giants apply lobby politicians to ensure priority access to power supplies.
Software engineers adapt the code used in servers, clients & infrastructure to minimise power consumption, making efficiency gains through clever use of compression and caching.

In this scenario, Moore's law continues unabated: the computing power of a chip doubles every two years,
while our *consumption* of computing power doubles every year.
We're still fucked.

### The social fix

> Engineering is the discipline of creating/reproducing socio-political power structures.

We know that software has great economic power by it's sheer ubiquity.

We know that it must have psychological power - just look at anyone chasing the digital dragon, scrolling endlessly through instagram.

We see that the problem lies in the way technology is used, and the way that people interact with power - both political and electrical.

To fix the climate, we need to fix ourselves.

### POST_CARBON_FUTURE.V0.patch

Making software *and people* compatible with our post-carbon future is no easy task.
As a first step, we must open our eyes to the compounding challenges which lie ahead.

Our patch adds a little metric to the corner of your UI.
Whether on a website in a brower, a mobile app, at the dashboard of your server or the dashboard of your car, you see something like this:

```
  /----------------------\
  | 1.23g carbon emitted |
  |     since            |
  |   2021-05-19 09:40   |
  \----------------------/
```

Unobtrusive yet inescapable, this little counter ticks slowly up, estimating the cumulative carbon emitted by your application - servers, mobile devices, routers, air conditioning...

It's not much, but it makes an intractable *and* invisible problem just a little bit more visible.

It's a start.
