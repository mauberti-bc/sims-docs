---
layout: default
title: Add Sampling Information
nav_order: 4
parent: Getting Started
permalink: /docs/getting-started/add-sampling-information
---

# Add Sampling Information

Sampling information includes locations, methods, and time periods, all of which are required to understand where, when, and how you collected your data. Without sampling information, it is difficult to interpret and extend the value of your data.

### Sampling Locations

Sampling Locations describe where you sampled and may have any of the following geometry types:

- Point, like a camera trap
- Line, like a transect
- Polygon, like a grid cell

There might be ambiguity in the geometry type of your Sampling Location. For instance, if you walked a zigzag transect through a grid cell, your Sampling Location could be the transect or the grid cell, depending on how much of the grid cell you covered. We suggest using the geometry type that makes the most sense given your objectives and sampling strategy.

{: .note}

We recommend only using polygonal sampling locations if you fully surveyed that area. Otherwise, consider using a line as your sampling location to more accurately reflect where you sampled.

### Sampling Methods

A Sampling Method describes how you collected data at a Sampling Location. You can add multiple Sampling Methods to a Sampling Location, which is useful if you measured multiple ecological variables at a site. For instance, you might have conducted an hour-long point count for birds _and_ deployed an acoustic recording device at the same Sampling Location.

You can enter additional method-dependent attributes to a Sampling Method to capture important details. For example, if your method is Distance Transect, you can enter the distance threshold over which you excluded species from your transect. Similarly, if your method is Camera Trap, you can enter information about the bait that you placed in front of the camera, if any.

### Sampling Periods

A Sampling Period decribes when exactly a Sampling Method was done. You can add multiple Sampling Periods to a Sampling Method in case you paused sampling, either intentionally as part of your Sampling Method or for a different reason like poor weather.

It is important to enter precise Sampling Periods to understand your sampling effort. Did you not observe black bears before lunch because there were no black bears or you didn't sample then? Being able to answer this question in your own context will allow for more valuable insights from your data.

### Sampling information is hierarchical

A Sampling Period applies to a specific Sampling Method, and a Sampling Method applies to a specific Sampling Location. This hierarchy gives you the flexibility to manage diverse sampling information in a single Survey, but it also means that you will need to enter Sampling Period information for each Sampling Method and Sampling Location.

You can quickly enter a lot of sampling information by [uploading Sampling Locations in bulk](). The best way to benefit from bulk uploading your Sampling Locations depends on your sampling information:

- If all of your Sampling Locations have the same Sampling Methods and Sampling Periods, you can [add all sampling information in one step]().
- If only some of your Sampling Locations have the same Sampling Methods and Sampling Periods, you can group similar Sampling Locations into [spatial files and bulk upload each file separately]().
- If your Sampling Locations differ only in their Sampling Periods, you can bulk upload Sampling Locations and [edit the Sampling Periods]().

<a class="float-left" href="./create-surveys">
Previous: Create Surveys
</a>
<a class="float-right" href="./add-species-observations">
Next: Add Species Observations
</a>
