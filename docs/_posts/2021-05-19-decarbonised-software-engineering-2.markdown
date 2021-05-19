---
layout: post
title:  "Decarbonised Software Engineering 2"
date:   2021-05-19 08:33:51 +0200
---

Read [part 1](_posts/2021-05-16-decarbonised-software-engineering.markdown) first.

### Even winning feels like losing

Lets consider the following scenario:

Following massive popular revolution, hydrocarbon-based capitalism is wiped out overnight. 
The EU transitions immediately to a renewable-based energy economy. 
What happens to the rest of the economy - and specifically the underlying software?

The vast majority of existant software is designed with the underlying assumption that our power grid is always-available and high-load.
Much of the world's computation occurs in enormous data centres across the globe which depend upon a constant and reliable power supply.
This infrastructure which handles almost all online interaction from your twitter feed to your amazon shopping cart
would be simply unable to continue existing in the post-hydrocarbon economy:

The most popular renewable energy sources (wind & solar) have pretty serious limitations: unreliability & low power density.
In adverse weather conditions they simply don't function, 
and far more physical power sources are required compared to fossil-fuel/nuclear power.
These issues may be *mitigated* by having a well-connected grid spanning a large geographical area as well as accurate weather prediction,
to minimise the impact of local conditions upon power output.
However, accurate weather prediction is an early casualty of the climate crisis, and technological solutions to even-out grid usage 
are beset by their own problems:
 - massive batteries to store renewable-generated energy are expensive and come with their own hefty carbon price-tag
 - nuclear (fission) power generation has insufficient uptake as well as it's own considerable political and technical problems

The world we have constructed around commodified data is simply incompatible with our post-hydrocarbon future.
This seems like a pretty serious problem; as software engineers, what are we to do? 
Two approaches spring to mind, depending on what exactly we take **engineering** to mean.

#### The technocratic fix

Engineering is a means of solving business problems to generate profit. 
Therefore we are looking to maintain our existing economic system under new conditions.
Power for our data centres is expensive or unavailable? Fine, just pass this on to the consumer.
Tech giants simply charge more via ad-tech to cover the rising cost of electricity, 
and use political pressure to ensure priority access when electricity is unavailable.
We software engineers adapt the code used in servers (data centres) and clients (laptops, mobile phones)
and infrastructure (routers) to minimise power load, making efficiency gains through clever use of compression and caching.

In this scenario, Moore's law continues unabated: the computing power of a chip doubles every two years, 
while our *consumption* of computing power doubles every year. We're still fucked.

#### The social fix

Engineering is a discipline concerned with the creation and reproduction of socio-political power structures.
We know that software has economic power from it's ubiquity.
We know that it must have psychological power - just look at anyone chasing the digital dragon, scrolling endlessly through instagram .
We see that the problem lies in the way technology is used, the way that people interact with power both political and literal.

To fix the climate, we need to fix ourselves.

### POST_CARBON_FUTURE.V0.patch

Making software *and people* compatible with our post-carbon future will be no easy task.
As a first step, society at large must open it's eyes to the inevitable future and the challenges which await.

Our patch adds a little metric to the corner of your UI.
Whether on a website in a brower, a mobile app, at the dashboard of your server or the dashboard of your car, you see something like this:

```
  /----------------------\
  | 1.23g carbon emitted |
  |     since            |
  |   2021-05-19 09:40   |
  \----------------------/
```

Unobtrusive yet inescapable, this little counter ticks slowly up, tracking the cumulative carbon emitted by your application.
It's not much, but it makes an intractable *and* invisible problem just a little bit more visible.

It's a start.
