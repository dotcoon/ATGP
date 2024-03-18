# PHG RF Range Circles - Appalachian Trail



## Overview

PHG stands for Power-Height-Gain (and directivity) which is all  you need to calculate the relative RF range of a station.  The most important parameter being Height Above Average Terrain.  Because the FCC has a rigorous method of mathematically calculating, some people think that HAAT takes on some exact, almost mystical meaning.   When in fact, it is just the simple Height of your antenna over the surrounding area that it serves.  Notice that Height above sea-level means absolutely nothing.  It is your heigh over everything around you that is important.

## Digipeaters and PHG

The most important use of PHG is in visualizing what area is covered by different digipeaters.

The default plot of all PHG Range circles is at the "half-size" scale which is much more appropriate for mobiles who have multipath, fading and other problems that shorten their usable range.  Secondly, by displaying the range circles at half-size, it keeps the map from being too cluttered.  So even though the circles between digis above do not overlap, they do probably have connectivity.

The most practical use of PHG circles is determining a path to get from point A to point B or in determining the number of hops that are needed to  get to a given area.

## Hops Determination

The diagrams within this section provide a one-time snapshot of the number of hops for the most recent packet heard from each digipeater at the time the diagram was produced. By watching it over a while, it is easy to see what digis (and therefore areas) you can hit with N number of hops.

## Path Tracing

Another very useful display of PHG data is during a TRACE display. This not only shows the path that a packet took to get to you , but also the PHG range circles of each of the digis so you can see how the network is working. The use of non-tracing WIDEn-N paths for the last several users almost killed this capability, but under the New n-N Paradigm, now all paths will be traceable and so this is a very neat display for monitoring the performance of your network.

PHG Circles ARE Ham Radio

To me, playing around with the maps and PHG data from everyone is most of what APRS on RF is all about. It gives you a window on the RF environment and a way to visualize who can see whom and what kind of station they have.  Even the Kenwood's display PHG data. 

 Some purists rightly claim that these circles are not perfect and cannot possibly represent the actual range of each station, but that was never their intent.  Their intent was to be a  *relative* indication  of the approximate range of a station so that hill-top stations would clearly stand out over low stations with marginal antennas.

Combined with the offset feature to allow for directivity or for obstructions and local  terrain, the PHG feature of APRS can be made to quite realistically  represent the usable range of most stations.  PHG data is a fundamental part of the APRS protocol and should be included in all fixed station packets and displayed in all programs.

de WB4APR, Bob
