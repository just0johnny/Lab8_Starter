# Lab8-Starter

## Page URL

URL: 

## Explore Question

Q: How are graceful degradation and service workers related?

A: Graceful degradation and service workers are very related
as they function somewhat like a failsafe system for pages
in order to provide functionality when certain parts fail.
Graceful degradation is more like the concept described above,
while service workers are a part of implementation with
graceful degradation, as they (at least the way we used it)
allow for offline use through the cache, which provides
functionality for the website. This is a perfect form of
graceful degradation because of course, having reliable
network access with the recipe data (in our case) is ideal,
but if unavailable, then we can use the service worker's
cache to still provide functionality with some degradation
(the offline data *might* be outdated). In short, the way
I understand it is that they are related in the sense that
they basically work as the back-up systems for a page by
sacrificing certain features to still provide functionality.