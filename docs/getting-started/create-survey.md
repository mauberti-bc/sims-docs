---
layout: default
title: Creating Surveys
nav_order: 3
parent: Getting Started
permalink: /docs/getting-started/create-survey
---

# **Creating Surveys**

Surveys store information about distinct ecological activities and are made to reflect true ecological surveys. As such, Surveys may contain sampling information, species observations, and uniquely marked animals.

## Sampling information

Sampling information includes locations, methods, and time periods, all of which are required to understand where, when, and how you collected data. Without sampling information, it is difficult to know how to best analyze your data.

### Sampling locations

A sampling location can be a point, like a camera trap, line, like an aerial transect, or polygon, like a grid cell.

If there is ambiguity in whether you sampled a line or polygon, you should use the geometry type that makes the most sense given your objectives and sampling strategy. For example, if you walked a zigzag transect throughout a grid cell, your sampling location could be the transect or the grid cell.

{: .note} We recommend only using polygonal sampling locations if you fully surveyed that area. Otherwise, consider using a line as your sampling location to more accurately reflect where you sampled.

## Sampling methods

Sampling Methods describe how you collected data. You can add multiple Sampling Methods to a Sampling Location, which is useful if you measured multiple ecological variables. For example, you might conduct a point count for birds _and_ deploy an acoustic recording device at the same Sampling Location, which you would enter as two different methods, each with their own Sampling Periods.

{: .note } We are developing Sampling Method attributes that let you record more details about your method, such as the distance threshold over which you excluded species from your transect survey or whether you placed bait in front of your camera trap.

## Sampling Periods

Each Sampling Method can have multiple Sampling Periods describing the start and end time of your Survey.

Sampling Periods are important to understand your sampling effort. Does your Survey not include any moose observations in the morning because there were no moose or you didn't sample then? This question is critical to get the most value out of your data.
